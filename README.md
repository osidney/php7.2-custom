# php7.2-custom
Instalação PHP 7.2 Custom

apt update && apt install php7.2-fpm php7.2-xml php7.2-bz2 php7.2-zip php7.2-mysql php7.2-intl php7.2-gd php7.2-curl php7.2-soap php7.2-mbstring php7.2-bcmath -y

wget https://github.com/sidneydevelop/php7.2-custom/archive/master.zip

unzip master.zip

cd php7.2-custom-master/

cp php.ini /etc/php/7.2/fpm/
cp www.conf /etc/php/7.2/fpm/pool.d/
cp php72.conf /etc/nginx/common/
