![tests](https://github.com/naveen-bharathi/ordinal-numbers/workflows/tests/badge.svg?event=push) ![License](https://badgen.net/npm/license/@naveen-bharathi%2Fordinal-numbers?color=blue) ![GitHub issues](https://img.shields.io/github/issues/naveen-bharathi/ordinal-numbers)
 <!-- ![weekly downloads](https://badgen.net/npm/dw/@naveen-bharathi%2Fordinal-numbers?color=blue&icon=npm)  -->
 ![dependencies](https://badgen.net/david/dep/naveen-bharathi/ordinal-numbers?color=green) 
 <!-- ![dependents](https://badgen.net/npm/dependents/@naveen-bharathi%2Fordinal-numbers?color=green)  -->
 ![publish size](https://badgen.net/bundlephobia/minzip/@naveen-bharathi/ordinal-numbers?color=blue)

# ordinal-numbers

A javascript module to get ordinal numbers like 1st, 2nd and 3rd.

## Installation

if you are using npm, run
```
npm install --save @naveen-bharathi/ordinal-numbers
```

or

if you are using yarn package manager, run
```
yarn add @naveen-bharathi/ordinal-numbers
```

## Example

Get the ordinal of **`1`**.

```javascript
import getOrdinalNumber from '@naveen-bharathi/ordinal-numbers'; // ES6
// or
const getOrdinalNumber = require('@naveen-bharathi/ordinal-numbers'); // ES5

const ordinalOfOne = getOrdinalNumber(1);

console.log(ordinalOfOne);
// outputs ==> 'st'
```

Get the ordinal of **`2`**.

```javascript
import getOrdinalNumber from '@naveen-bharathi/ordinal-numbers'; // ES6
// or
const getOrdinalNumber = require('@naveen-bharathi/ordinal-numbers'); // ES5

const ordinalOfTwo = getOrdinalNumber(2);

console.log(ordinalOfTwo);
// outputs ==> 'nd'
```

## Parameters

#### getOrdinalNumber(number)
- **number** **{Object | Array}** - Number for which the ordinal is needed.


## Tests

![tests](https://github.com/naveen-bharathi/ordinal-numbers/workflows/tests/badge.svg?event=push)


## Open Issues

![GitHub issues](https://img.shields.io/github/issues/naveen-bharathi/ordinal-numbers)


## LICENSE

MIT License

Copyright (c) 2020 Naveen Bharathi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
