# null_or_empty

[![npm version](https://badge.fury.io/js/null.svg)](https://badge.fury.io/js/null)

[![Node CI](https://github.com/jirimicvl/null/actions/workflows/main.yml/badge.svg?branch=master)](https://github.com/jirimicvl/null/actions/workflows/main.yml)

[![Node CI](https://github.com/jirimicvl/null/actions/workflows/main.yml/badge.svg?branch=master&event=Test)](https://github.com/jirimicvl/null/actions/workflows/main.yml)


A Node.js package that checks, if a given string is null or empty.

## Usage

First, install the package using npm:

    npm install @skalwar/null_or_empty --save

Then, require the package and use it like so:

    var isNullOrEmpty = require('@skalwar/null_or_empty');

    console.log(isNullOrEmpty("")); // true
    console.log(isNullOrEmpty(null)); // true
    console.log(isNullOrEmpty(undefined)); // true

    console.log(isNullOrEmpty("Hello World")); // false

## License

MIT
