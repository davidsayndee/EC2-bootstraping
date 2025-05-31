# EC2 Bootstrapping Project

This project demonstrates how to automate the setup of an Apache web server on an Amazon EC2 instance using a bash script provided in the EC2 User Data field during instance launch.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [License](#license)

## Project Overview

The goal of this project is to showcase how to use EC2 User Data to automate the installation and configuration of a web server upon instance launch. This approach is useful for automating server setups and can be extended to more complex deployment scenarios.

## Technologies Used

- Amazon EC2
- Amazon Linux 2
- Bash scripting
- Apache HTTP Server
- Git & GitHub

## Project Structure


## Usage

1. Launch a new EC2 instance using the AWS Management Console.
2. In the "Configure Instance" step, scroll down to "Advanced Details."
3. Paste the contents of `user-data.sh` into the "User Data" field.
4. Ensure the security group allows HTTP (port 80) traffic.
5. Launch the instance and, once running, access the public IP address in a web browser to see the "Hello from EC2" message.

## Screenshots

![EC2 Instance Running](screenshots/ec2-instance-running.png)
![Web Server Output](screenshots/web-server-output.png)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
