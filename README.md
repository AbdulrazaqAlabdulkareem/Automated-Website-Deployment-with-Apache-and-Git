# Automated Website Deployment with Apache and Git

This script automates the deployment of a website using Apache (httpd) and Git on a CentOS/RHEL-based Linux server. It prompts the user for a GitHub repository URL, installs necessary dependencies, clones the repository, and deploys the website.

## Usage

1. Clone or download this repository.
2. Make the script executable: `chmod +x deploy_website.sh`
3. Run the script: `./deploy_website.sh`

Follow the interactive prompts to enter the repository URL and initiate the automated deployment process. The script will install Apache (httpd), Git, clone the repository, and configure the website for deployment.

## Prerequisites

- CentOS/RHEL-based Linux system
- Internet connectivity to access GitHub repositories

## Notes

- Ensure that both HTTP and HTTPS are enabled in the security group settings for successful deployment.
- The script assumes CentOS/RHEL-based Linux distributions and uses `yum` for package management.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it according to the terms of the license.
