# Authenticated service

## Description
The Authenticated Service handles authenticated requests using JSON Web Tokens (JWT) uniquely created from a PEM file. It utilizes a JSON Web Key Set (JWKS) to validate JWT signatures and offers two routes:` /` for an open route and` /protected `for a route requiring a valid JWT.

## Features

- JWT authentication with JWKS validation using a PEM file.
- Open route at `/` for general information.
- Protected route at `/protected` requiring a valid JWT for access.
- Error handling for 404, 401, and 500 HTTP status codes.


## Prerequisites
- Node.js
- npm (Node package manager)


## Installation
1. Clone the repository:
   ``git clone https://github.com/alyona-shirpal/test-jwk.git``
2. Install dependencies `` npm install ``
3. Run the project ``npm run start ``
