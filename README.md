# Robo Vault web

It is a document storage with scheduler to invoke document actions

#Prerequiremens

##Oracle linux 8

###PHP

yum install php php-json php-cli php-zip php-pdo php-xml wget unzip

###Composer

php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer

https://linuxize.com/post/how-to-install-and-use-composer-on-centos-7/

###Apache

yum install httpd
chkconfig httpd on
service httpd start
service httpd stop

###Composer
https://symfony.com/doc/current/setup/web_server_configuration.html

composer require symfony/apache-pack


# Install