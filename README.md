# 🚀 Terraform EC2 Web Server Deployment

This project automates deployment of an EC2 instance on AWS using **Terraform (Infrastructure as Code)**.  
It installs Apache web server and hosts a custom webpage automatically using **User Data** script.

---

## 🎯 Project Objective
- Automate cloud infrastructure provisioning
- Deploy a web server without manual AWS console steps
- Learn Terraform basics, AWS IAM, networking & automation

---

## 🧩 Architecture
'''Text'''
Terraform ➝ AWS Provider ➝ EC2 Instance ➝ Apache Web Server ➝ Public IP ➝ Browser Access

🛠 Technologies Used
Tool / Service	Purpose
Terraform	IaC automation
AWS EC2	Cloud compute resource
Apache	Web hosting
SSH & Security Groups	Access & networking
⚙️ Terraform Commands Used
terraform init
terraform plan
terraform apply


To remove resources and avoid costs:

terraform destroy

🌐 Website Output

“Hello from Shreya’s Terraform EC2!” 🎉

<img width="1920" height="1080" alt="Output1" src="https://github.com/user-attachments/assets/c4ff136c-d430-4a04-a2c6-8ea90341df24" />
<img width="1920" height="1080" alt="Output2" src="https://github.com/user-attachments/assets/641fed87-8802-4e39-a19c-86b8b2d47035" />









📘 Resources Created

EC2 Instance

Security Group with Port 22 & 80 open

Automated Apache installation

📌 Key Learnings

✔ Infrastructure as Code (IaC)

✔ Cloud networking fundamentals

✔ IAM roles & access credentials

✔ Deployment automation

✔ Debugging AWS permissions & region issues

🧹 Cleaning Up

• Run the command to avoid charges:

• terraform destroy


⭐ Resume Points

• Automated AWS infrastructure using Terraform (IaC) to deploy EC2-based web server.

• Configured secure networking & automated Apache installation through user-data script.

• Delivered fully operational public website using zero manual console configuration.

🚀 Future Enhancements

• Add Load Balancer + Auto Scaling Group

• Variable/Modules implementation

• CI/CD Terraform pipeline


👩‍💻 Author

Shreya S V

Cloud & DevOps Engineer Aspirant ☁️✨

GitHub: https://github.com/ShreyaSV-12
