# posts-api-walkthrough

jr-posts-api-walkthrough
The purpose of this project is to gain some practical experience on how to build an basic API server with Express.js, by achieving the following tasks:

build up a basic express server with GET, POST, PUT, DELETE methods

utilise middleware

structure the project, so it's more maintainable and clean

There is no database in this project, memory used to mimic the data storage

Live demo
Web Interface

API Docs (Swagger)

Journey begins
0. Setup
simply fork this project to start with or create your own

there are progressive branches for each step listed below, switch to them at your need

1. Basic express server
init the project and install express
npm init --yes

npm i express
setup an express server

build up the server with CRUD operations

2. Create fake data model
we don't have database, but we will mock one
3. Format our code
explain a better project structure

extract common logic to middleware

extract routes into separate modules

4. Understand the ENV variables
NODE_ENV

PORT

dotenv

5. Other essential packages
helmet

morgan

winston (may not covered)

cors

6. Deploy
pm2

heroku

7. Other topics (explore yourself)
Swagger
eslint
