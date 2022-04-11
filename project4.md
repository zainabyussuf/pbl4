# PROJECT 4 DOCUMENTATION

`sudo apt update`

`sudo apt upgrade`

`sudo apt install -y nodejs`

`sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6`

`echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.4.list`

`sudo apt install -y mongodb`

`sudo service mongodb start`

![mongodb](./images/mongodb.PNG)


`sudo systemctl status mongodb`

![active](./images/mongodsactive.PNG)


`sudo apt install -y npm`

`sudo npm install body-parser`

`mkdir Books && cd Books`    

`npm init`

`vi server.js`

`sudo npm install express mongoose`

`mkdir apps && cd apps`

`vi routes.js`

`mkdir models && cd models`

`vi book.js`

`cd ../..`

`mkdir public && cd public`

`vi script.js`

`vi index.html`

`cd ..`

`node server.js`

![nodejs](./images/nodejs3300.PNG)

[public ip](https://100.26.146.80:3300)

![completed](./images/complete%20project4.PNG)

![book](./images/book.PNG)

































