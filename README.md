# EC2 Bootstrap Project with User Data

This project demonstrates how to automate the setup of an Apache web server on an Amazon EC2 instance using a bash script passed through the EC2 User Data field during instance launch.

## 🚀 Project Overview

When the EC2 instance is launched, a bootstrap script:
- Updates the system with `yum update -y`
- Installs Apache (`httpd`)
- Starts the Apache web server
- Configures the instance to display a simple "Hello from EC2" message in a browser

## 🛠️ Technologies Used

- **Amazon EC2**
- **AWS CLI**
- **Bash Script**
- **User Data Bootstrap**
- **Amazon Linux 2**
- **Apache Web Server**

## 📁 Project Structure
ec2-bootstrap-project/
├── user-data.sh # Bash script for EC2 bootstrap
├── README.md # Project overview and instructions
└── screenshots/ # Optional: Screenshots of EC2 and web output

