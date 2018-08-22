# Customer Management

This customer management project manage the customer, With in this project I am using Angular and call a Node.js RESTful service. Below are the concept that I am using with in this project

## Angular Concepts Covered

* Using TypeScript classes and modules
* Modules are loaded with System.js
* Using Custom Components
* Using the Http object for Ajax calls along with RxJS observables
* Performing GET, PUT, POST and DELETE requests to the server
* Working with Angular service classes for Ajax calls
* Using Angular databinding and built-in directives

## Software Requirements To Run Locally 

* Node.js 6.10 or higher
* MongoDB 3.2 or higher

### Running the Application Locally

1. Install Node.js (6.10 or higher) and MongoDB (3.2 or higher) on your dev box

    * Node.js: https://nodejs.org
    * MongoDB: https://docs.mongodb.com/manual/administration/install-community

#For REST API But currently serving data from file system
1. Execute `mongo`(On Ubuntu system for window and mac run `mongod`) to start the MongoDB daemon if it's not already running

1. Install Nodemon and Gulp: `npm install nodemon gulp -g`

1. Run `npm install` to install app dependencies

1. Run the following Gulp task to copy required Angular modules into the `dist` folder: 

    `gulp copy:libs`

1. Run `npm start` to compile the TypeScript and start the server

1. Browse to http://localhost:3000

