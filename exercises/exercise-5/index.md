# Exercise 5 - Final Exercise :muscle:

### Duration
`4 days`

### Code Review
`Trainer + 3`

## Summary
So, we’ve covered the file system, http, using express to handle our routes and requests, and now it’s time to build something real! In this final exercise you will cover many topics that will enhance your usage of Node and your understanding of building a web app server.

### Guidelines
`live-reload with nodemon is recommended and even a must. JWT or any kind of authentication is not needed. Make SURE you are using npm scripts to properly build, run locally, test, lint. Babel? use it, it is important to transpile your code and build it. Linting your code is a very important thing to do, so in this exercise you will start using ESLint, find the right config.
Remember, in this final exercise you are tested for composing a scalable and well-structured application as well as for the usage of new libraries and creating a REST API.`

### Recommended modules
`express, mongoose, body-parse and every other express middleware of your choosing, nodemon, dotenv`

### Code Style
`Every api has it’s own folder? every model has it’s own folder? every type of file has it’s own folder? it’s your project, your choosing, but be able to explain why your structure scales and why it’s clean and neat`

## Tasks
* Set up a node.js project with ESLint and an express.js web server running on a port of your choosing
* Set up express with the proper middlewares
* Create models using mongoose and a somehow seed your database
    * User ({_id, name: {first,last}, email})
    * Todo ({_id, title, content})
        * The user holds an array of todos or the todo holds the user posted it?
* Implement an api using your models
    * CRUD
* you can implement your own ‘client’ to test your API or even better, write test suites!


