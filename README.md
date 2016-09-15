# romans
A no dependency, simple lib for converting from decimal notation to roman numerals and back again

[![Build Status](https://travis-ci.org/qbunt/romans.svg?branch=master)](https://travis-ci.org/qbunt/romans)
[![codecov](https://codecov.io/gh/qbunt/romans/branch/master/graph/badge.svg)](https://codecov.io/gh/qbunt/romans)
[![dependencies](https://david-dm.org/qbunt/romans.svg) ](https://david-dm.org/)

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)

## Install
Simply run the following in the terminal:
```
$ npm i --save romans
```

## Usage
```
var roman = require('romans');
roman.romanize(454);
// returns:"CDLIV"

roman.deromanize("CDLIV")
//returns: 454

roman.allNumerals
// property containing [ 1000, 900, 500, 400, 100, 90, 50, 40, 10, 9, 5, 4, 1 ]

roman.allChars
// property containing all roman numeral characters
// [ 'M', 'CM', 'D', 'CD', 'C', 'XC', 'L', 'XL', 'X', 'IX', 'V', 'IV', 'I' ]
```

## Tests
```
npm test
```