# Remove Trailing Zeros

[![NPM version][npm-image]][npm-url]
[![NPM downloads][downloads-image]][downloads-url]

Remove extra zeros from the end of a string or number

## Installation

```
yarn add remove-trailing-zeros
```

## Usage

```
import removeTrailingZeros from 'remove-trailing-zeros'

console.log('Are the same:', removeTrailingZeros('1,230.4000'')) // -> 1,230.4
```
## Examples

1 -> 1
10 -> 10
100. -> 100
100.0 -> 100
100.1 -> 100.1
100.10 -> 100.1
100.01 -> 100.01
100.010 -> 100.01
'1.2304000' -> 1.2304

## License

ISC

[npm-image]: https://img.shields.io/npm/v/remove-trailing-zeros.svg?style=flat
[npm-url]: https://npmjs.org/package/remove-trailing-zeros
[downloads-image]: https://img.shields.io/npm/dm/remove-trailing-zeros.svg?style=flat
[downloads-url]: https://npmjs.org/package/remove-trailing-zeros
