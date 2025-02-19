<h1><a href="https://github.com/qbunt/romans" target="_blank"><img width="150" src="logo.png"></a></h1>

A no dependency, simple lib for converting from decimal notation to roman numerals and back again

[![quality](https://api.codacy.com/project/badge/Grade/3642e8e1b1b940ce8faa04bb7083f0fb)](https://app.codacy.com/app/qbunt/romans?utm_source=github.com&utm_medium=referral&utm_content=qbunt/romans&utm_campaign=Badge_Grade_Dashboard)
[![tests](https://github.com/qbunt/romans/actions/workflows/nodejs.yml/badge.svg)](https://github.com/qbunt/romans/actions/workflows/nodejs.yml)
[![coverage](https://codecov.io/gh/qbunt/romans/branch/master/graph/badge.svg?token=kD6QSvKfTe)](https://codecov.io/gh/qbunt/romans)
[![deps](https://david-dm.org/qbunt/romans.svg) ](https://david-dm.org/)
[![npm](https://img.shields.io/npm/v/romans)](https://www.npmjs.com/package/romans)

[![forthebadge](https://forthebadge.com/images/badges/you-didnt-ask-for-this.svg)](https://forthebadge.com)

## Install
With [yarn](https://yarnpkg.com/) installed, run:

```shell
$ yarn add romans
```    

## Usage
```js
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
## Testing

```shell
$ yarn test
```

## License
[MIT](./LICENSE)
