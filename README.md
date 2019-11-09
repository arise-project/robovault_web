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

https://tecadmin.net/install-symfony-3-framework-on-centos/

###Composer
https://symfony.com/doc/current/setup/web_server_configuration.html

composer require symfony/apache-pack
composer require symfony/web-server-bundle --dev

###Symfony

curl -LsS https://symfony.com/installer -o /usr/local/bin/symfony
chmod a+x /usr/local/bin/symfony

php bin/console server:run


# Install
