# MyEAN-Test

MyEAN stack using [meanjs-mysql](https://github.com/esatemre/meanjs-mysql)

MEAN.JS version: 0.4.2

### Install Node and NPM using NVM

```shell
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.1/install.sh | bash

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh"

nvm install 6.10.1 // for latest stable version nvm install stable

```

### Setup

```bash
// MySQL server install
wget https://dev.mysql.com/get/mysql-apt-config_0.8.3-1_all.deb

dpkg -i mysql-apt-config_0.8.3-1_all.deb

sudo apt-get install -f //or apt-get install mysql-server

sudo service mysql status //if not running: sudo service mysql start


```

```shell
//other dependencies
sudo apt-get install ruby-full

npm install -g bower

npm install -g grunt

gem install sass

npm install -g grunt-cli
```

```shell
//meanjs-mysql
git clone https://github.com/esatemre/meanjs-mysql.git meanjs

mysql --user=user --password=password dbname
```

```sql
CREATE DATABASE `mean-dev`;
```


```shell
grunt
```

Vois kokeilla myös MEAN.io:sta versio josta Mongoose vaihettu Sequalizeen: [mean-stack-relational](https://github.com/jpotts18/mean-stack-relational)
