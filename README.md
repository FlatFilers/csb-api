# csb-api
Simple JSON API for getting data within our CSB examples

In order to call data, use the URL https://my-json-server.typicode.com/flatfilers/csb-api/<end-point>

Each key within the db.json is its own endpoint that can be hit.

To see it work, go to your browser and paste the following code:

fetch('https://my-json-server.typicode.com/flatfilers/csb-api/users')
  .then(response => response.json())
  .then(json => console.log(json))
 
For more info about how to create new data models, this uses <a href="https://my-json-server.typicode.com/">my-json-server.typicode.com</a> under the hood.
