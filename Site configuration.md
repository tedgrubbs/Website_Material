# Create new user
`adduser ted`
`usermod -aG sudo ted`

# MySQL Setup
https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-20-04

# Restore database
https://www.mysqltutorial.org/mysql-adminsitration/mysql-restore-dump/
`source <db file>` 

# Install Apache
https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-20-04

# TLS
https://certbot.eff.org/

# Install PHP
`apt install php`
`apt install php-mysqlnd`

# Configure PHP extensions
https://www.howtosolutions.net/2021/07/install-wordpress-php-apache-mysql-on-windows-for-beginners/#1_Install_PHP
`php-config --extension-dir` < finds extension directory

# Wordpress
Just decompress wordpress folder back into /var/www/html/