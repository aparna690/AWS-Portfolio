1.Update the System
sudo yum update -y

2. Install Apache Web Server
sudo yum install httpd -y
3. Start Apache Service
sudo systemctl start httpd

4. Enable Apache on Boot
sudo systemctl enable httpd

5. Check Apache Status
sudo systemctl status httpd

6. Navigate to Web Root Directory
cd /var/www/html

7. Remove Default Apache Page
sudo rm -rf *

8. Set Proper Permissions
sudo chown -R ec2-user:ec2-user /var/www/html

9. Restart Apache After Uploading Template
sudo systemctl restart httpd

Key Conversion Step

To convert the .pem file to .ppk format for use in WinSCP, I used:

PuTTYgen

Load .pem file

Save private key as .ppk
