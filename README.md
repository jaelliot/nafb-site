# Mobile Legal Solutions Website

## Overview
Mobile Legal Solutions provides professional notary services. This repository hosts the static site, ready for deployment to an AWS S3 bucket using Terraform.

## Getting Started

### Prerequisites
- Terraform installed
- AWS CLI configured with appropriate permissions

### Deployment
To deploy the website to AWS S3:

1. **Initialize Terraform:**
   Navigate to the `infrastructure-files` directory and run:
   ```bash
   terraform init
   ```
2. **Apply Terraform Configuration:**
   Deploy the infrastructure with:
   ```
   terraform apply
   ```
   Confirm the deployment when prompted.

### Local Development
- HTML content is located in the site-assets directory.
- Modify CSS and JavaScript in the site-assets/assets directory.
- Use Sass for styling by editing files in the site-assets/assets/sass directory.

### Contributions

To contribute:

Fork the repository.
Create a new branch for your feature.
Make changes and test.
Submit a pull request with a clear description of the changes.