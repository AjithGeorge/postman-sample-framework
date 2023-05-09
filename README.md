# Sample Node.js project for postman script execution

This is a sample Node.js project that demonstrates how postman scripts can be run in CI/CD pipelines.

## Installation

To install this project, clone the repository from GitHub:

`git clone https://github.com/AjithGeorge/postman-sample-framework.git`

Then, navigate to the project directory and install the dependencies using npm:

`npm install`

All the dependencies are listed in the package.json file.

## Prerequisites:

1. Postman Application installed.
2. Node and Npm installed. (Only required for reporting purpose)

## Usage

To start the application, run the `runner.js` file using Node.js:

`node runner.js`

This should start the execution of the test scripts.

## Overview:

The solution has, tests and scenarios for the RESTful API at https://api.restful-api.dev/objects:

    GET /objects

    Scenario: Retrieve a list of all objects
    Test case:
        Send a GET request to https://api.restful-api.dev/objects
        Verify that the response status code is 200 OK
        Verify that the response contains a JSON array of objects
        Verify that each object has the expected properties [Schema Validation] (e.g. "id", "name", "data")
    
    GET /objects/:ids

    Scenario: Retrieve a specific object by ID/IDs
    Test case:
        Send a GET request to https://api.restful-api.dev/objects/:id (replace ":id" with the ID/IDs of an existing object)
        Verify that the response status code is 200 OK
        Verify that the response contains the requested number of json objects (Count should match the requested number of Id/Ids)
        Verify that the response contains only the requested ID/IDs
        Verify that the each object has the expected properties [Schema Validation] (e.g. "id", "name", "data")
## Note
The collection can be run from simply importing the same into postman too, the set up in this code is to enable the CI/CD integration along with the same.
