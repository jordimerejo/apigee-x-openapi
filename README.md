# apigee-x-openapi
Apigee X Proxy Bundle to OpenAPI Specification v3.1.0 conversion tool

Apigee Edge Proxy to OpenAPI 2.0 (formerly known as Swagger) conversion tool. This project used to be called `apigee2swagger` prior to the specification becoming part of the [OpenAPI Initiative](https://openapis.org).

# Note
This is a adaptation from source code Anil Sagar https://github.com/anil614sagar/apigee2openapi to covert GCP Apigee X to OpenApi v3.10

# Installation

You can install `apigee-x-openapi` either through npm or by cloning and linking the code from GitHub.  This document covers the installation details for installing from npm.

## Installation from npm

The `apigee-x-openapi` module and its dependencies are designed for Node.js and is available through npm using the following command:

### From a Terminal Window:
```bash
$ sudo npm install -g apigee-x-openapi
```


#### Examples
1. Download proxy bundle from Edge instance and generate OAI
```bash
$ apigee2openapi -d /Users/Anil/Desktop/
```
2. Use local proxy bundle (zip) to generate specs
```bash
$ apigee2openapi -d ~/Documents/GlobalWeather -l ~/Documents/GlobalWeather.zip -n GlobalWeather -e https://msebai-test.apigee.net
```

#### Articles

https://community.apigee.com/articles/10044/apigee2openapi-a-nodejs-command-line-tool-to-gener.html

#### How to Contribute ?

Submit issues / patches here https://github.com/anil614sagar/apigee2openapi

Q & A ? http://community.apigee.com/
