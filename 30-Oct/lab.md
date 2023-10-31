## Dynamic User Data Script - Metadata


- User data script
```bash
#!/bin/bash
var_os=`curl -s http://169.254.169.254/latest/meta-data/ami-id`
if [ $var_os == "ami-06006e8b065b5bd46" ] # add amazon ami id
then
sudo yum -y update
sudo yum -y install httpd
sudo yum -y install git
sudo systemctl start httpd
sudo systemctl enable httpd
sudo git clone https://github.com/ravi2krishna/ecomm.git /var/www/html/
else
sudo apt -y update
sudo apt -y install nginx
sudo rm /var/www/html/*.html
sudo git clone https://github.com/ravi2krishna/food.git /var/www/html/
fi
```
