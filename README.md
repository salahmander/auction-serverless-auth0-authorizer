# auction-serverless-auth0-authorizer

serverless-auth0-authorizer

<h1 align="center">Serverless Framework Auth0 Authorizer</h1>
<p align="center">
  <i><strong>A modern, ES6-friendly Lambda Authorizer ready for integration with Serverless Framework and Auth0.</strong></i>
  <br/>
  Based on the <a href="https://github.com/serverless/examples/tree/master/aws-node-auth0-custom-authorizers-api">serverless/examples/aws-node-auth0-custom-authorizers-api</a> example.
</p>

## Features

- Test front-end application
- Private endpoint for testing
- Public endpoint for testing
- ES6-friendly

## Getting started

### 1. Clone the repository (or generate a serverless project)

```sh
cd auth-service
```

### 2. Install dependencies

```sh
npm install
```

### 3. Create `secret.pem` file

This file will contain your Auth0 public certificate, used to verify tokens.

Create a `secret.pem` file in the root folder of this project. Simply paste your public certificate in there.
