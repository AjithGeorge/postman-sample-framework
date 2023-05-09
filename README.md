# Sample Node.js project for postman script execution

This is a sample Node.js project that demonstrates how postman scripts can be run in CI/CD pipelines.

## Installation

To install this project, clone the repository from GitHub:

`git clone https://github.com/AjithGeorge/postman-sample-framework.git`


Then, navigate to the project directory and install the dependencies using npm:

`cd sample-nodejs-project`

`npm install`


## Usage

To start the application, run the `runner.js` file using Node.js:

`node runner.js`

This should start the execution of the test scripts.

## Configuration

The application can be configured by modifying the `environmentConfig.json` and the `runner.js`files. The available configuration options are:

- `baseUrl`: The baseurl to which tests are targeted.
- `retry`: true/false -Whether to retry any of the failed tests again. Default false.


## Areas Covered:
- Create API Tests Using [Postman Scripts](https://learning.postman.com/docs/postman/scripts/test-examples/)
- Run tests using Postman Collection Runner and through [Newman](https://www.npmjs.com/package/newman) CLI tool
- Generate Report using [Newman reporter](https://www.npmjs.com/package/newman-reporter-html)
- Customized Newman Reporter -[htmlextra](https://github.com/DannyDainton/newman-reporter-htmlextra)
- Assertions using [Chai Assertion Library](https://www.chaijs.com/api/)

Main Reference: [DannyDainton: All-Things-Postman](https://github.com/DannyDainton/All-Things-Postman#example-guides)

## Overview:
The solution tests APIs for,


## Prerequisites:
1. Postman Application installed.
2. Node and Npm installed. (Only required for reporting purpose)

## Contributing

Contributions to this project are welcome! If you would like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.


