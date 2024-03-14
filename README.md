# nginx-container-automation-by-ansible
Ansible playbook for automating the installation of Docker and running an Nginx web server as a container. Simplify the deployment process with this playbook, which handles Docker installation, Nginx image pulling, volume creation, and container setup. Ideal for streamlining web server deployment tasks."
# Nginx Container Automation with Ansible

This Ansible playbook automates the setup of an Nginx web server as a Docker container. It simplifies the deployment process by handling Docker installation, pulling the Nginx image, creating volumes, and starting the container.

## Usage

1. **Clone Repository**: Begin by cloning this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/aanan27/nginx-container-automation-by-ansible.git

Modify Playbook (Optional): If necessary, customize the docker-nginx.yaml playbook file to match your specific environment requirements. You can adjust variables, such as Nginx configuration settings or mounted volume paths, to suit your needs.

Run Playbook: Execute the playbook on your target host by running the following command in your terminal:

bash
Copy code
ansible-playbook docker-nginx.yaml
This command will initiate the automation process, which includes installing Docker, pulling the Nginx image from the Docker Hub registry, creating necessary volumes, and starting the Nginx container.

Prerequisites
Before using this playbook, ensure that the following prerequisites are met:

Target Host: You need access to a CentOS or Ubuntu system where you want to deploy the Nginx container. Ensure SSH access to the target host is available.

Local Environment: Ansible must be installed on your local machine to execute the playbook. If Ansible is not installed, refer to the official Ansible documentation for installation instructions.

