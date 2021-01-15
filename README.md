![Postman Logo](https://www.pngkit.com/png/detail/206-2063294_the-postman-logo-is-available-in-png-svg.png)
# Postman_TestProject

#### Postman Version 7.36.1

## Description
#### Postman_TestProject is used for testing some basic HTTP Methods in Postman:
* GET
* POST
* PUT
* PATCH 
* DELETE

#### Target website URL is: https://reqres.in/

## This `project` contains the following:
* Collection One

## `Collection One` contains 5 folders:
* GET
* POST
* PUT
* PATCH 
* DELETE

## `GET folder` contains the following requests:
* GET List Users
* GET Single User
* GET Single User Not Found
* GET List Resource
* GET Single Resource
* GET Single Resource Not Found
* GET Delayed Response

## `POST folder` contains the following requests:
* POST Create
* POST Register Successful
* POST Register Unsuccessful
* POST Login Successful
* POST Login Unsuccessful

## `PUT folder` contains the following request:
* PUT Update

## `PATCH folder` contains the following request:
* PATCH Update

## `DELETE folder` contains the following request:
* DELETE Delete

## API Documentation 

https://documenter.getpostman.com/view/9609130/TVzPkHre

* Run in Postman
* Choose Postman for Web
* Choose Slobodan's Workspace

## How to run from Command Line with Newman

1. Download and Install node.js
* Useful links:
  `https://nodejs.org/en/download/`
2. Install npm
3. Install Newman
  * `npm install -g newman`
4. Export Collection as Json file
5. In terminal go to location of Collection json file
6. Run command
  * `newman run https://www.getpostman.com/collections/8de50556315f6ff5f38b -e QA_env.json`


