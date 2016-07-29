# PHP 7 FPM

## Instalação
```shell
sudo add-apt-repository ppa:ondrej/php
sudo apt-get update
sudo apt-get install php7.0-fpm php7.0-cli php7.0-mcrypt php7.0-mysql php7.0-mbstring php7.0-xml php7.0-zip
```

## Configuração
```shell
sudo vim /etc/php/7.0/fpm/php.ini
cgi.fix_pathinfo=0
sudo service php7.0-fpm restart
```
