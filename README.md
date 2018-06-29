This repo/package was created by following steps at https://codeburst.io/how-to-create-and-publish-your-first-node-js-module-444e7585b738

Number Formatter
=========
[![Build Status](https://travis-ci.org/ortizmj12/number-formatter.svg?branch=master)](https://travis-ci.org/ortizmj12/number-formatter) [![Coverage Status](https://coveralls.io/repos/github/ortizmj12/number-formatter/badge.svg?branch=master)](https://coveralls.io/github/ortizmj12/number-formatter?branch=master)

A small library that adds commas to numbers

## Installation

  `npm i @ortizmj12/number-formatter`

## Usage

    var numFormatter = require('@ortizmj12/number-formatter');

    var formattedNum = numFormatter(35666);
  
  
  Output should be `35,666`


## Tests

  `npm test`

## Contributing

In lieu of a formal style guide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code.
