# Capstone Infrastructure as Code (IaC)

This repository automates the provisioning of infrastructure, web applications, and their components using a variety of tools.



## Infrastructure Diagram:
<img width="812" alt="Screenshot 2024-09-09 at 10 22 40 AM" src="https://github.com/user-attachments/assets/b4d39d8e-116c-4a5d-af41-d1d38cb08d88">

## Tools Used

- **Terraform**: Infrastructure as Code tool for provisioning cloud resources.
- **Git**: Version control system.
- **Ansible**: Configuration management and automation.
- **EKS (Elastic Kubernetes Service)**: Managed Kubernetes service by AWS.
- **Jenkins**: Continuous Integration and Continuous Deployment (CI/CD) tool.
- **Prometheus**: Monitoring and alerting toolkit.
- **Splunk**: Data analysis and monitoring platform.
- 
### Script Process
<img width="737" alt="Screenshot 2024-09-09 at 10 23 07 AM" src="https://github.com/user-attachments/assets/a66fc3cc-1bd7-4985-b69c-86fddee87562">

## Getting Started

To set up the environment and run the automation scripts, follow these steps:

### Prerequisites

1. **KodeKloud Playground**: Start a KodeKloud Playground and log in using the provided credentials.
2. **Cloud Shell Instance**: Initiate a cloud shell instance.

### Setup and Execution

1. **Switch to Superuser**

   Due to storage limitations of the `cloudshell-user`, perform the following steps outside of the `cloudshell-user` (e.g. root):

   ```bash
   sudo su

2. **Clone the Repository and Run the Script**

   ```bash
   cd /home
   git clone --branch <branch_name> <repo_url>
   cd <repo>
   chmod +x final-script-v2.sh
   ./final-script-v2.sh <git_user> <git_pat> <repo_url> <access_id> <access_key>
