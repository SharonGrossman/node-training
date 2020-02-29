# Exercise 3 - Express

### Duration
`1.5 days`

### Code Review
`Trainer + 1`

## Summary
Enter express.js. a popular framework for creating and running a web server in Node.js. In this exercise you will create working web server that handle different requests in different ways.

### Recommended modules
`express, body-parser and any other express middleware you choose to use`

## Tasks
* Create an express server on port 9090
* Implement a logging middleware that logs every requests that is directed at your server
* Add 2 routes
   * ‘/’ is a route that serves (statically) the public folder that contains:
        * index.html
        * index.js
        * styles.css
    * ‘/todos’ is a route that sends a sample JSON file. just create a sample JSON file with some keys and values, and let the browser display it (without downloading)
    * 404 page - index.html that indicates that this route is not found upon your web server
