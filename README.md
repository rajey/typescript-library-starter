# Typescript Library Starter

[![Build Status](https://travis-ci.org/rajey/typescript-library-starter.svg?branch=master)](https://travis-ci.org/rajey/typescript-library-starter) [![Maintainability](https://api.codeclimate.com/v1/badges/2453f31853bf80cca1cf/maintainability)](https://codeclimate.com/github/rajey/typescript-library-starter/maintainability) [![Test Coverage](https://api.codeclimate.com/v1/badges/2453f31853bf80cca1cf/test_coverage)](https://codeclimate.com/github/rajey/typescript-library-starter/test_coverage)

Typescript based boilerplate for developing javascript library in typescript. This lets you write your codes in typescript to take advantage of the language features and in the end build the library that can be accessed/used in following ways;

- ES2015 module. i.e. `import <somethingFromLibrary> from 'libraryName'`

- CommonJS module. i.e. `require('libraryName')`

- Global variable when included through `script` tag

# Installation

Run `npm install` to install all necessary packages to start the library

# Building a library

Run `npm run build` to build the library. Build artifacts will be stored in the `dist/` directory.

# Running unit tests

Run `npm test` to execute the unit test, this starter is configured with [jest](https://jestjs.io/docs/en/getting-started)

# Documentation

Run `npm run docs` to generate your library documentations. Documentation pages will be store in `docs/` directory.
