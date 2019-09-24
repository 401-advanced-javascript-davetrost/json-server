# json-server

## Build a working JSON Server
* Installed `json-server` globally - json-server is a quick and dirty way to set up an API
* The data fed into json-server contains the following fields:
  * `categories`
    * `_id`, `name`, `display_name`, `description`
  * `products`
    * `_id`, `category`, `name`, `display_name`, `description`
* The resulting api responds to the following endpoints:
  * `/categories`  GET, POST
  * `/categories/:id/` PUT, DELETE
  * `/products`  GET, POST
  * `/products/:id/` PUT, DELETE

## Connect a web server to the json-server API
* The web-server used for testing is this: [React Application](https://codesandbox.io/s/w638oyk7o8)
* This app shows my API Data!

## Generate Swagger Documentation
* Swagger's Inspector tool was used to test and document the api
* The following URL contains the information that was used to generate documentation: [Swagger Hub](https://app.swaggerhub.com/apis/DaveTrost/disc-golf-discs-api/0.2#/)
* The file `./docs/swagger.json` contains the source info for the Swagger Docs
