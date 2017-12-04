## Introduction

It's a simple contact app implemented with React and Redux.

The app shows how to use Redux and basic concepts (action, reducer and store) of Reudx.


## Installation

`npm install`


## Run

For this simple app, there are several startup scripts in package.json:

- "clean": "rimraf dist",
- "build:webpack": "cross-env NODE_ENV=production webpack --config webpack.config.prod.js",
- "build": "npm run clean && npm run build:webpack",
- "prod": "npm run build && node server.js",
- "dev": "node devServer.js",
- "start": "npm run dev",
- "lint": "eslint src || exit 0"


### Running Dev Server

Use `npm start` or `npm run dev` command to start the dev server.

Redux Devtools are enabled by default in development:

- `CTRL+H` Toggle DevTools Dock
- `CTRL+Q` Move DevTools Dock Position

![issue](https://cloud.githubusercontent.com/assets/5880320/14728909/aa80f3bc-086b-11e6-8276-339e9805ca93.PNG)


### Building and Running Production Server

Use `npm run prod` to build and then run production server.



# intuit-contacts-manager
This will make managing Intuit contacts a breeze

By Rekha, for Intuit as a take home programming challenge.

# Designing the Application
This application will be built using modern front-end tools and technologies
The back end will be seeded and mocked out with sample data.

### Technologies:
 1. ES6: the language the project is written in
 2. Node: the environment the code gets executed in
 3. Webpack: the file bundler when building the project
 4. ReactJS: the front end framework used to design the user interface
 5. Redux: the state management library to handle your data
 6. Bootstrap: the components used to interact with the web page ( menu's, buttons, inputfields)
  
### Supporting Libraries
 1. Lodash: an utility library to work with data in javascript
  
## Testing tools
 1. Jest: used to write tests
 2. Enzyme: a utility library that helps write tests
 3. Chai: an assertion library
  
# Learning the technologies

## Day 1
#### CSS and HTML refresher:
1. Web Fundamentals: HTML and CSS
https://www.codecademy.com/tracks/web

2. Make a Website
https://www.codecademy.com/learn/make-a-website

3. Download tools: node, git, xcode, and vscode

## Day 2
learning javascript
https://www.codecademy.com/learn/introduction-to-javascript
focusing on data types and functions

## Day 3
learning javascript continued
https://www.codecademy.com/learn/introduction-to-javascript


## Day 4
deeper dive/refresh

#### Variables:
1. const 
2. let
#### Data Types:
1. __Object__: http://javascriptissexy.com/javascript-objects-in-detail/
  a. learning how to access properties in objects
  b. difference between key and a value
2. __Array__: https://learn.co/lessons/javascript-arrays
  a. learning how to access items in arrays 
  b. collections ( arrays with objects in them )
3. string
4. integer
5. boolean
6. __truthy values__
  a. how can a string, integer or boolean be truthy
7. __falsy values__
  a. how can a string, integer or boolean be falsy
8. __logical operators__

#### Functions: 
1. arrow functions
  a. when to use arrow functions instead of regular functions
  
## Day 5
1. refresh day 2-4, focus on difficult topics
2. __string templating__ 
3. __Object destructring__
4. Object destructuring default values
5. spreading object properties or array
6. recap blocks 

## Day 6
project start
1. find a react/redux boilerplate code that used webpack
2. Udemy course on advanced react

## Day 7
1. props
2. propTypes and defaultProps: https://reactjs.org/docs/typechecking-with-proptypes.html we need to pull in this library
3. containers vs components
4. action creators ( thunks )
5. reducers
6. mapStateToProps and mapDispatchToProps

## Day 8
1. bootstrap components: https://reactjs.org/docs/react-dom.html
2. eslint and linting using airbnbs style guide
3. debugging tools


## Day 9


## additional:
1. es6 (modern javascript ) https://www.youtube.com/watch?v=IEf1KAcK6A8
2. javascrip basics ( less modern javascript, less sugared syntax ) https://www.youtube.com/watch?v=_mj72QqsOs4
3. another javascript basics: https://www.youtube.com/watch?v=10ujZygJzMQ


## resources:
1. cheat sheet: https://devhints.io/es6
2. coding playground: https://codepen.io


