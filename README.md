# Demo_AWS_Code_Star

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)

---

## 📄 Project Description

**Demo_AWS_Code_Star** is a sample project demonstrating the deployment of a static HTML website using **AWS CodeDeploy** and **AWS CloudFormation** to an Amazon EC2 instance. This project includes configuration files and scripts to automate the deployment process.

---

## 📁 Repository Structure

Demo_AWS_Code_Star/
├── scripts/ # Deployment scripts
├── webpage/ # Static web assets
├── appspec.yml # AWS CodeDeploy configuration
├── buildspec.yml # AWS CodeBuild configuration
├── template.yml # AWS CloudFormation template
└── README.md # Project documentation


---

## ⚙️ How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/maumhmd-sh/Demo_AWS_Code_Star.git
cd Demo_AWS_Code_Star
```

### 2. Deploy Using AWS CloudFormation
- Open the AWS CloudFormation console.
- Create a new stack using the template.yml file.
- Follow the prompts to configure and deploy the stack.

### 3. Configure AWS CodeDeploy
- Ensure the `ppspec.yml` file is correctly configured for your application.
- Set up AWS CodeDeploy to deploy the website to your EC2 instance.

### 4. Access the Website
- After deployment is complete, access the website via the public IP or domain name of your EC2 instance.
- You should see the deployed static website.

---

## 📌 Features
- Automates deployment of a static website using AWS CodeDeploy.
- Infrastructure as code with AWS CloudFormation.
- Sample deployment scripts for smoother workflow.
- Easy to replicate for testing or demo purposes.

---
## 📝 License
This project is licensed under the MIT License.

## ❤️ Support
If you find this project helpful, give it a ⭐ on GitHub and share it with others!
