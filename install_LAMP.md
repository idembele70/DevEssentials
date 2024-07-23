install LAMP (Linux Apache Mysql Php)
================================

**Installing Apache 2**
1. Update package manager
```bash
sudo apt update
```
2. Install Apache
```bash
sudo apt install apache2
```
3. Go to http://localhost/
4. You should be able to see this page
![image](https://github.com/user-attachments/assets/37070e52-a068-45a0-af7c-2aad239c6db7)

**Installing MySQL**
1. Install mysql
```bash
sudo apt install mysql-server
```
2. Start MySQL interactive installation & follow the different steps to install it
```bash
sudo mysql_secure_installation
```
3. Create an admin user on MySQL & grant all privileges on each database
```bash
sudo mysql
```
```bash
CREATE USER 'EXAMPLE_USER'@'%' IDENTIFIED BY 'CUSTOM_PASSWORD';
```
```bash
GRANT ALL ON *.* TO 'EXAMPLE_USER'@'%';
```
4. To connect to MySQL with this new user
```bash
mysql -u EXAMPLE_USER -p
```

**Installing PHP**
1. Install PHP
```bash
sudo apt install php libapache2-mod-php php-mysql
```
2. Restart apache2
```bash
sudo systemctl restart apache2
```

**Source**
1. https://www.digitalocean.com/community/tutorials/how-to-install-lamp-stack-on-ubuntu
