# making info.php page
-----------------------

* manual steps
```
sudo apt update
sudo apt install apache2 -y
sudo apt install php libapache2-mod-php php-mysql -y
sudo -i 
echo "<?php phpinfo(); ?>" > /var/www/html/info.php
```
* libapache2-mod-php php-mysql, php, php-mysql are the dependencies of the php.info page.