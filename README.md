# quick-n-dirty-web-server
A bash script that installs quickly and dirty a web server on an *Ubuntu 20.04.x* installation.

Download the file and then: **chmod +x quick_server**

Then execute like this: **./quick_server**

It will run the commands with sudo and will initially ask for your user password, then it will install the following packages.

- git
- mysql-server-8.0
- certbot
- nginx
- redis-server
- php7.4-fpm 
- php7.4-bcmath 
- php7.4-bz2
- php7.4-cli
- php7.4-common
- php7.4-curl
- php7.4-gd
- php7.4-json
- php7.4-mbstring
- php7.4-mysql
- php7.4-xml
- php7.4-zip

It will also download **composer** and install it globally and will also grab and install **NodeJS** from [Nodesource](https://github.com/nodesource/distributions).

**Why the installation of Redis, Composer, and NodeJS?**
I use this script to develop Laravel projects and those packages are needed for my purposes.

# Keep in mind that this server will not be secured and is for development purposes ONLY!!
