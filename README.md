# is-capitalized [![Build Status](https://travis-ci.org/tjmehta/is-capitalized.svg)](https://travis-ci.org/tjmehta/is-capitalized) [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](http://standardjs.com/)
Checks if an input string is a capitalized or not.

# Installation
```bash
npm install --save is-capital
```

# Usage
```js
var isCapitalized = require('is-capitalized')

isCapitalized('Aaa') // true
isCapitalized('Bbb') // true
isCapitalized('Ccc') // true

isCapitalized('A') // true
isCapitalized('B') // true
isCapitalized('C') // true

isCapitalized('a') // false
isCapitalized('b') // false
isCapitalized('c') // false

// edgecase
isCapitalized('AAA') // true
isCapitalized('BBB') // true
isCapitalized('CCC') // true

var strict = true
isCapitalized('AAA', strict) // false
isCapitalized('BBB', strict) // false
isCapitalized('CCC', strict) // false
```

# License
MIT

