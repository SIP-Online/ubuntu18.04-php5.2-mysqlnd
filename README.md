<h1 align="center">
  Ubuntu 18.04 LTS (Bionic Beaver) PHP 5.2.17 with support "mysqlnd"
</h1>

## Installing required libraries
sudo apt-get install libxml2-dev libxslt1-dev libcurl4-openssl-dev libjpeg-turbo8-dev libpng-dev libxpm-dev \\<br />
libicu-dev libgd-dev libkrb5-dev libc-client2007e-dev libmcrypt-dev libmhash-dev

## Building and Install
git clone "https://github.com/SIP-Online/ubuntu18.04-php5.2-mysqlnd.git"<br />
cd "ubuntu18.04-php5.2-mysqlnd"<br />
chmod 0755 "configure.php5.2-Ubuntu18.04.sh"<br />
./configure.php5.2-Ubuntu18.04.sh
