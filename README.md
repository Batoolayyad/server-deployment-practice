# server-deployment-practice

Node Ecosystem, TDD, CI/CD
Application development in the Node.js ecosystem, including the writing of modular code using CommonJS modules, writing tests to assert code quality, setting up and working in a "Continuous Integration" environment ([Github Actions](https://github.com/Batoolayyad/server-deployment-practice/actions)).

## Learning Objectives
### Students will be able to
#### Describe and Define
* Node and the V8 Engine
#### Execute
* Setup a Node.js Package using npm
* Create CommonJS modules
* Create a simple express server
* See passing tests via GitHub actions (CI)
* Deploy to Heroku using CD: 

## Today's Outline
## Notes:
- we made a request and test it 
- 500: reffere to internet error
- 400: reffere to bad request
### Importing and Exporting Modules
If one module exports a function or an object ...

// person.js
const person = {};

person.walk = function() {
  return 'walking';
}

module.exports = person;
Another module can import and use that function or object

const human = require('./person.js'))
console.log( human.walk() );  // prints 'walking'

## CI/CD - Continuous Integration and Deployment
- **Github Actions URL:**([Github Actions](https://github.com/Batoolayyad/server-deployment-practice/actions)).
- **Deploy to Heroku URL: main-server-deployment-practice:** [main-server-deployment-practice](https://m-server-deployment-practice.herokuapp.com/)
- **Deploy to Heroku URL: dev-server-deployment-practice:** [dev-server-deployment-practice](https://m-server-deployment-practice.herokuapp.com/)
