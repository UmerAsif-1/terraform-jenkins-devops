### [Terraform Jenkins DevOps](https://github.com/UmerAsif-1/terraform-jenkins-devops)
- **Description:**  
  Project Overview:  
  This project automates the creation of an AWS infrastructure using Terraform, setting up a web server with Jenkins and integrating SonarQube for static code analysis. Docker is used for containerization, and Trivy is employed for security scanning. The infrastructure includes security groups, EC2 instances, and essential services, making it a fully automated DevOps pipeline ready for CI/CD integration.

  **Technologies Used:**
  - AWS (EC2, Security Groups)
  - Terraform (for Infrastructure as Code)
  - Jenkins (CI/CD)
  - Docker (Containerization)
  - SonarQube (Static Code Analysis)
  - Trivy (Container Security Scanning)

  **Setup Instructions:**
  1. Clone the repository.
  2. Set up AWS credentials.
  3. Run `terraform init` to initialize Terraform.
  4. Execute `terraform apply` to provision the infrastructure.
  5. Use `./install.sh` to set up Jenkins, Docker, and other tools.

  **Features & Benefits:**
  - Automated infrastructure provisioning in AWS.
  - CI/CD pipeline integration using Jenkins.
  - Container security scanning with Trivy.
  - Static code analysis using SonarQube.
  - Secure and scalable web server setup.

  **Future Improvements:**
  - Add automatic scaling for EC2 instances.
  - Integrate more security tools like AWS GuardDuty.
  - Implement CloudWatch for monitoring and logging.

  **Why This Project?**
  This project showcases my skills in AWS cloud infrastructure, Terraform, CI/CD, containerization with Docker, and security best practices. It is designed to automate the deployment process and ensure secure, scalable infrastructure for continuous integration.
