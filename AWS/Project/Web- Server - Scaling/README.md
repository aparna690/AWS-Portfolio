Multi-OS Web Server Deployment and Automation on AWS EC2
Overview

This project demonstrates the deployment of web servers across multiple operating systems using Amazon Web Services EC2. The environment includes Windows and Linux instances configured to host custom web pages, enable secure access, and implement basic automation through shell scripting.

The objective was to simulate a real-world cloud setup where different operating systems coexist within the same infrastructure.

Architecture Summary

The infrastructure consists of:

1.Windows EC2 Instance (t3.small)

Configured with Internet Information Services (IIS) to host a custom HTML web page.

2.Red Hat Linux EC2 Instance

Configured with Apache HTTP Server to host a static web page.

3.Amazon Linux EC2 Instance

Configured with Apache and enhanced with shell scripting for automation.

All instances were deployed within AWS EC2 and accessed using their public IP addresses.

Implementation Details
1. Web Server Configuration

Installed IIS on the Windows instance.
Installed Apache (httpd) on Red Hat and Amazon Linux instances.
Enabled and started web services.
Deployed custom HTML pages in the appropriate web root directories.

2. Secure Access
   
Configured SSH access for Linux instances using key pairs.
Verified secure remote login without password authentication.
Managed services and files directly through terminal access.

3. Automation with Shell Scripting
A shell script was created on the Amazon Linux instance to automate:
System updates
Web server restart

Deployment of updated web content

Testing and Validation

1.Verified web pages via browser using public IP addresses.

2.Confirmed Apache and IIS services were active and running.

3.Executed automation script and validated real-time updates.

4.Ensured SSH connectivity remained stable and secure.

Key Skills Demonstrated

1.AWS EC2 provisioning

2.Windows and Linux server configuration

3.Apache and IIS setup

4.SSH configuration and key management

5.Shell scripting for automation

6.Basic cloud infrastructure validation

Project Outcome
The project successfully established a multi-operating system web hosting environment within AWS. It demonstrates foundational cloud deployment skills, secure configuration practices, and automation capabilities applicable to real-world infrastructure scenarios.

Future Enhancements

1.Application Load Balancer integration

2.Auto Scaling configuration

3.CloudWatch monitoring

4.Static asset storage using Amazon S3
