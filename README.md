# Creme-Brulee-Project
Advocating safe and healthy use of cannabis products 

# Instructions: 
* open config.json file under config folder in the root directory, modify the following config with your database info:
```
"development": {
    "username": "root",
    "password": "changeMe",
    "database": "changeMe_db",
    "host": "127.0.0.1",
    "dialect": "mysql"
```
* create a schema in mysql workbench/command line.  Sequelize will take care of creating tables based on models created in server/models folder.
* run npm install
* run npm start
