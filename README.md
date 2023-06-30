# Node.js Session by Audumbar Kabade sir

## Day1: node-session

node -v <br>
npm -v <br>

install EXPRESS framework <br>
https://expressjs.com/en/starter/generator.html <br>
$ npm install -g express-generator <br>
express -h <br>

express --view=ejs 

express --no-view Demo1

Go inside the Demo1 folder and type "code .", it'll open Project in VSCode

npm install(installs packages)

set DEBUG=demo1:*

npm start
==> project starts running in localhost:3000

callback function==> passing fn as argument 

morgan ==> is the logger
 
 npm install nodemon
 
 npm start

 ```
 go to package.json file and change the following line
{
  "name": "demo1",
  "version": "0.0.0",
  "private": true,
  "scripts": {
    "start": "node ./bin/www"
  },
```
change to 
```
{
  "name": "demo1",
  "version": "0.0.0",
  "private": true,
  "scripts": {
    "start": "nodemon ./bin/www"
  },
```
goto app.js and comment the line
```//app.use(express.static(path.join(__dirname, 'public')));```

```
goto routes/index.js and change to
router.get('/', function(req, res, next) {
  res.send({ title: 'Express' });
});
```
<br>

==> vvvvvi, this will write everything on the html page, every code written

truncate vs delete in dbms
middleware concept in node.js

to send data using post method, we need to use postman

post == put
---

delete every folder except only 3 files
app.js
package-lock.json
package.json

edit app.js file
----------------------------------
hw
----------------------------------
1. array crud 
2. what is node.js
3. what are different http methods and its status code like 404
4. get vs post
5. var, let vs const
6. normal fn vs arrow fn
7. repl, how to create server

9595986033
Audumbar Kabade (best teacher)
<img src="dynamic_hr.gif">

# Day 2

steps to create project
1. go to D drive, open cmd

```
express --no-view project
cd project
npm i
set DEBUG=project:*
```

express validator

install bcrypt for encrypting passwords

Sequelize: is a Node. js-based Object Relational Mapper that makes it easy to work with MySQL, MariaDB, SQLite, PostgreSQL databases, and more. An Object Relational Mapper performs functions like handling database records by representing the data as objects.

Multar: is a node middleware for handling multipart/form-data , which is primarily used for uploading files.

Nodemailer: for sending emails
