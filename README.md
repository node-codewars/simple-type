simple-type
========
[![build status](https://travis-ci.org/node-codewars/simple-type.svg)](http://travis-ci.org/ruanyl/simple-type)
[![NPM version](https://badge.fury.io/js/simple-type.svg)](http://badge.fury.io/js/simple-type)

enhance javascript typeof

## Installation

This module is installed via npm:

``` bash
$ npm install simple-type
```

## Example Usage

``` js
var simpleType = require('simple-type');

simpleType([1,2,3]) === 'array' // true
simpleType({name: 'ruan', age: 12}) === 'object' //true
simpleType(new Date()) === 'date' // true
//string, number, null, function, regexp, boolean, undefined are also supported
```
