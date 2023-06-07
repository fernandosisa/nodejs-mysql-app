# Node.js and MySQL CRUD with Login

A web application built with Node.js and MySQL that allows CRUD (Create, Read, Update, Delete) operations and includes a login system for user authentication.

## Table of Contents

- [Features](#features)
- [Installation](#installation)

## Features

- CRUD Operations: Perform Create, Read, Update, and Delete operations on the MySQL database.
- User Roles: Supports different user roles with varying permissions.
- Database Connectivity: Establishes a connection with MySQL database for data storage and retrieval.
- User-Friendly Interface: Intuitive and user-friendly interface for easy interaction with the application.

## Installation

video tutorial: https://www.youtube.com/watch?v=qJ5R9WTW0_E

password es:    admin
en mysqlworkbench

npm init --yes          desde la consola para crear el package.json
npm i express express-handlebars express-session mysql express-mysql-session morgan bcryptjs passport passport-local timeago.js connect-flash express-validator
npm i nodemon -D

"dev": "nodemon src/"      se agrega esta linea en package.json para que pueda correr el comando de nodemon, (corre el archivo index.js que este en /src)
npm run dev                         para correr el servidor y ahora se puede entrar a http://localhost:4000/

1. Clone the repository: `git clone https://github.com/your-username/nodejs-mysql-crud-login.git`
2. Navigate to the project directory: `cd nodejs-mysql-crud-login`
3. Install dependencies: `npm install`  esto creara la carpeta node_modules
4. `npm run dev`                         para correr el servidor y ahora se puede entrar a `http://localhost:4000/`