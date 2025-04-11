# Infrastructure-Provisioning-with-Terraform-and-Docker
A simple project demonstrating infrastructure provisioning using Terraform and Docker. It pulls an Nginx image and deploys a container accessible via port 8081.
# Terraform + Docker: Nginx Deployment

This project demonstrates how to provision infrastructure using **Terraform** and **Docker** to deploy an **Nginx** web server.

## 🔧 Prerequisites

- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [Terraform](https://developer.hashicorp.com/terraform/downloads)
- Internet connection (to pull the `nginx` image)

## 📁 Project Structure

terraform-docker-demo/ ├── main.tf ├── README.md

markdown
Copy
Edit

## 📜 main.tf Explanation

- **docker_image**: Pulls the latest `nginx` image.
- **docker_container**: Creates a Docker container named `my-nginx` and exposes port `8081`.

## 🚀 How to Use

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/terraform-docker-demo.git
   cd terraform-docker-demo
Initialize Terraform:

bash
Copy
Edit
terraform init
Apply the configuration:

bash
Copy
Edit
terraform apply
Type yes when prompted.

Open your browser and visit:

arduino
Copy
Edit
http://localhost:8081
You should see the default Nginx welcome page.

🧹 To Clean Up
To remove the created resources:

bash
Copy
Edit
terraform destroy
📸 Preview

Happy coding 🚀
Made with 💻 by Sathwik Chinta

vbnet
Copy
Edit

Let me know if you want to add a license or `.gitignore` file too!
