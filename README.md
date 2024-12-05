[![Build Status](https://travis-ci.org/prettier/prettier.svg?branch=master)](https://travis-ci.org/prettier/prettier)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

## Contents

1. [Description](#description)
1. [Requirements](#requirements)
1. [Team Members](#team-members)
1. [Development](#development)
1. [License](#license)

## Description
> This is an e-commerce/retail front end application. The initial focuses on providing the minimum viable product for the retail application. Features implemented are constrained to the consumer experience which enables fundamental features, such as search, browse, add to cart, and checkout.

## Requirements
- Node 15.4.0

## Team Members
- [Shinan Sun](https://github.com/ShinanSun)
- [Sean Brazil](https://github.com/scbrazil)
- [Chris Thackrey](https://github.com/ChrisThackrey)
- [Jerrick Ravelo](https://github.com/CheddarChzKeys)

### Development
> Development requires eslint (for linting) and Jest (for testing).  All dev dependencies are listed in the package.json file.

> Contributions are welcome, please add tests and make sure that all tests pass.

### Installing Dependencies

From within the root directory:

```sh
npm install -g webpack-cli
npm install
```
> Make sure to create a `.env` configuration file with your private GitHub API Access Token listed as `TOKEN=<your_token>`

- Run `npm run watch` to build the bundles and watch for changes.

- Run `npm start` to start nodemon and watch for changes.

### Testing
- Run `npm test` to run jest testing suites.

### Deployment
- Run `npm run build`
- Run `node server.js` to start the server
