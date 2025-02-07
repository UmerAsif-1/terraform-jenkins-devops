### [Terraform Jenkins DevOps](https://github.com/UmerAsif-1/terraform-jenkins-devops)

#### **Project Overview**
This project automates the setup of a **DevOps pipeline** in AWS using **Terraform, Jenkins, SonarQube, Docker, and Trivy**. It provisions an **EC2 instance (T2 Large Ubuntu)**, configures a secure infrastructure, and integrates **CI/CD, static code analysis, and container security scanning**. The setup ensures efficient resource utilization while maintaining security best practices.

#### **Why T2 Large Ubuntu Instance?**
A **T2 Large instance (2 vCPUs, 8GB RAM, 30GB storage)** was selected because:
- Jenkins requires sufficient CPU and memory for smooth execution of CI/CD jobs.
- SonarQube is resource-intensive, needing extra RAM for analysis.
- Docker containers, including SonarQube and Trivy, need stable performance.
- It balances cost and performance effectively for small to medium-scale projects.

#### **Technologies Used**
- **Terraform** – Infrastructure as Code (IaC) to automate AWS resource provisioning.
- **AWS EC2 & Security Groups** – Compute instances and network security.
- **Jenkins** – CI/CD automation.
- **SonarQube** – Static code analysis.
- **Docker** – Containerization for Jenkins and SonarQube.
- **Trivy** – Container security scanning.

#### **Project Features**
- **Automated AWS Infrastructure:** Terraform provisions EC2 and security configurations.
- **CI/CD Pipeline:** Jenkins automates builds and deployments.
- **Static Code Analysis:** SonarQube scans code for bugs and vulnerabilities.
- **Security Integration:** Trivy scans Docker containers for security threats.
- **Scalable & Secure:** Security groups restrict access, ensuring a controlled environment.

#### **Setup Instructions**
1. Clone the repository.
2. Configure AWS credentials.
3. Run `terraform init` to initialize Terraform.
4. Apply the infrastructure with `terraform apply`.
5. Execute `./install.sh` to install Jenkins, Docker, SonarQube, and Trivy.
6. Access Jenkins via `http://<EC2-Public-IP>:8080`.
7. SonarQube is available at `http://<EC2-Public-IP>:9000`.

#### **Future Improvements**
- Implement **auto-scaling** for EC2 instances.
- Integrate **CloudWatch** for monitoring and logging.
- Enhance security with AWS **GuardDuty and IAM role-based access**.

#### **Why This Project?**
This project demonstrates **DevSecOps best practices** by automating infrastructure provisioning while integrating **continuous integration, security scanning, and static analysis**. It ensures a robust, scalable, and secure **DevOps pipeline** for efficient software delivery.
