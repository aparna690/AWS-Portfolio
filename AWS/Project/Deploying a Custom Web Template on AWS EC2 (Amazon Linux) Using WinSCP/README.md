Project Overview

This project demonstrates how to deploy a custom static web template on a cloud server using Amazon Web Services. A virtual machine was launched through Amazon EC2 with Amazon Linux as the operating system.

The server was configured as a web host, and a custom HTML template was uploaded securely using WinSCP after converting the SSH key format with PuTTYgen.

The website was successfully hosted and accessed through the public IP address of the EC2 instance.

Objectives

1.Launch and configure an EC2 instance

2.Manage SSH key pairs securely

3.Install and configure a web server

4.Upload website files using secure file transfer

5.Host a live static website on the cloud

Technologies Used

1.Amazon Web Services

2.Amazon EC2

3.Amazon Linux

4.Apache HTTP Server

5.WinSCP

6.PuTTYgen

7.Git & GitHub

Implementation Steps

1.Created an EC2 instance using Amazon Linux.

2.Configured security groups to allow SSH (Port 22) and HTTP (Port 80).

3.Downloaded the .pem private key during instance setup.

4.Converted the .pem file to .ppk format using PuTTYgen.

5.Connected to the server via WinSCP using the .ppk key.

6.Installed and started the Apache web server.

7.Replaced default web directory content with a custom HTML template.

8.Verified deployment using the public IP address in a web browser.

Key Skills Demonstrated

1.Cloud instance provisioning

2.Linux server configuration

3.SSH authentication and key management

4.Web server installation and configuration

5.Secure file transfer

6.Basic cloud deployment workflow

Challenges Faced

1.Understanding SSH key format conversion

2.Setting correct permissions for web directory

3.Ensuring proper security group configuration

4.Verifying Apache service status

Outcome

A fully functional static website was deployed on an EC2 instance and made publicly accessible. This project demonstrates foundational cloud infrastructure and web hosting skills.
