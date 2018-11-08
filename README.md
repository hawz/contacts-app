# Simple AngularJS Contacts app

## Simple SPA
It's a single `main.js` file, I know it could be structured way better, it's not a complex project, but just simple thing to show how to use basically all the features provided by AngularJS

- Controllers
- Routing using `ui.router`
- Services
- Factories and ngResource to map RESTful resources
- custom Directives with isolated `$scope`
- Third party libraries customized inside `app.config` blocks

## What's inside
- bower.json - project dependencies (I know it's the 21st century, it's an old AngularJS sample project, c'mon :))
- ./src - where the simple code of the application is.
- ./src/libs/ - required libraries for the app

## Instructions
run `bower install` from the project root, then `cd` into src and run a simple http-server

`python -m SimpleHTTPServer` or `http-server` (the last one should be installed as a global npm package)

Navigate to localhost and that's it.