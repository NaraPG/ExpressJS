# Express.js

## This repository
> In this course we learned about what express.js is in a more extended way and how to implemet it in our project 

#### What is express.js?
> Express is a minimal and flexible Node.js web application framework that provides a robust set of features to develop web and mobile applications. It facilitates the rapid development of Node based Web applications. 

#### Why use express.js
> With the help of Express.js, you can easily build different kinds of web applications in a short period of time. Express.js provides a simple routing for requests made by clients. It also provides a middleware that is responsible for making decisions to give the correct responses for the requests made by the client

## Hello world example with express.js

```
const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('Hello World!')
})

app.listen(port, () => {
  console.log(`Example app listening at http://localhost:${port}`)
})
```
## Concepts
> - Template engine
> - Pug
> - Static Files
> - CRUD
> - MongoDB Atlas
> - Middleware
> - Joi and Boom
> - JWT
> - Passport.js
> - Tests
> - Debugging


## Installing Express.js
> ```
> $ npm install express --save
> ```


## Dependencies
> - Install [VS Code](https://code.visualstudio.com/download)
> - Install [Node.js](https://nodejs.org/en/)
> - Install Express.js
> - Install [Postman](https://www.postman.com/downloads/)
> - Install [JSON Viewer](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh)
> - MongoDB Atlas
>    * Connect the server with the DB.
> 
>    * Create `.env` in the root path `/` file and your variables
```
DB_NAME=core-xyz.gcp.mongodb.net
DB_USER=db_user_value
DB_PASSWORD=db_password_value
```
> - Install nodemon
>   * Cloning with git or by using npm (the recommended way):
> ```
> npm install -g nodemon
> ```
>   * You can also install nodemon as a development dependency:
>   ```
>   npm install --save-dev nodemon
>   ```

## Run Code
> - Use `npm i` to install the project dependencies
> - For Windows use the command `cd [path]` and `npx nodemon [script]` to run the project automatically

## Technologies
> - JavaScript
> - CSS
> - Pug

_Created by Nara Peña Gámez._
