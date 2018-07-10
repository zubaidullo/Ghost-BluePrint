# Ghost-BluePrint

* apt-get install curl
* ca-certificates
* curl -L https://ghost.org/zip/ghost-latest.zip -o ghost.zip
* apt-get install unzip
* unzip ghost.zip
* mkdir /home/ghost/  – mkdir /var/lib/ghost
* mv * /home/ghost/    – mv * /lib/ghost
* apt-get install npm
* curl -sL https://deb.nodesource.com/setup_10.x | bash -
* apt-get install -y nodejs
* npm install –production
* apt-get install screen nginx
* nano /etc/nginx/sites-enabled/default
    proxy_pass http://127.0.0.1:2368;
* service nginx restart
* npm start –production
