Mongoose Items Example
======================

This example demonstrates Mongoose and Angular together:

- Connect mongoose to our local mongodb server and specify a database
- Define a model (with schema) in `models/item.js`
- Import our item model using `require()`
- Create an express application using `express()`
- Use `express.static()` to serve static content from `public/`
- Use `bodyParser()` to parse POST requests
- Add route handlers for `/items` (GET and POST handlers)
- Use `Item.find()` to query MongoDB and return all the documents in the `items` collection
- Use `new Item()` to create a new document in the `items` collection
- Use `promise.then()` to run code after asynchronous event

On the client-side (in `index.html`):
- Use the Angular CDN
- Use the Bootstrap CDN
- Create an Angular module (an Angular application)
- Create an Angular controller (`ItemCtrl`)
- Create a bootstrap panel
- Create a bootstrap row/column layout
- Use `ng-model` to bind input fields to `$scope` variables
- Use `ng-click` to run a scope function
- Use `$http.get()` to send a GET request to an express route running on our server
- Use `$http.post()` to send a POST request with an object as the payload
- Use `ng-repeat` to loop through an array
- Use expressions `{{item.name}}` to display scope variables

All of that in just over 100 lines of code!


### Install:

- Clone this repo
- `npm install`
- `node server.js`
