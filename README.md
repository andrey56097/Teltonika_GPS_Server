# Teltonika_GPS_Server (Node.js)
Simple GPS server for Teltonika's FMXXXX GPS device in Node.js

## INSTALL

* Create database in mysql
* Run GPS_DATA.sql script
* Insert IMEI in IMEI_ALLOW table and set allow to 1
* Configure a connection in gps.js
```javascript
var db_config = {
    host: '',
    user: '',
    password: '',
    database: '',
    insecureAuth: true
};
```
Also add to you mysql: 

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password'

* Run 'npm install' for installing all the project dependencies
* Run nodejs gps.js
* Run nodejs gps.js

Your socket listening port 5002 
