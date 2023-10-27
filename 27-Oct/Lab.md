## Lab 

### SSH Commands
- Use Following commands for SSH
```bash
chmod 400 key.pem
ssh -i key.pem username@public-ip-address
```


## Nginx Web Server
- WEB SERVER - A web server is computer software [ Nginx HTTP Server ] and underlying hardware  [ AWS Instance ] that accepts requests via HTTP (port 80)  to distribute web content.
- Web Server Setup
- Git Bash For : SSH
- Git Hub For : CODE
- Git For : DOWNLOAD CODE
- Follow below steps to host a web application

```bash
sudo ss -ntpl
sudo apt -y update
sudo apt -y install nginx
sudo ss -ntpl
ls /var/www/html
sudo rm /var/www/html/*.html
ls /var/www/html
sudo git clone https://github.com/ravi2krishna/ecomm.git /var/www/html
ls /var/www/html
```

## User Data
- https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/user-data.html

- User data script
```bash
#!/bin/bash
sudo apt -y update
sudo apt -y install nginx
sudo rm /var/www/html/*.html
sudo git clone https://github.com/ravi2krishna/ecomm.git /var/www/html
```
