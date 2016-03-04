# errorable-merchant [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url] [![Coverage percentage][coveralls-image]][coveralls-url]
> merchant errors for errorable

## Installation

```sh
$ npm install --save errorable-merchant
```

## Usage

```js
var errorable = require('errorable');
var errorableMerchant = require('errorable-merchant');
var Generator = errorable.Generator;
var cnErrors = new Generator(errorableOrder, 'zh-CN').errors;
var enUsErrors = new Generator(errorableOrder, 'en-US').errors;

// IdError
// NotLoggedIn
// NotFound
```
## License

MIT © [calidion](calidion.github.io)


[npm-image]: https://badge.fury.io/js/errorable-order.svg
[npm-url]: https://npmjs.org/package/errorable-order
[travis-image]: https://travis-ci.org/Errorable/order.svg?branch=master
[travis-url]: https://travis-ci.org/Errorable/order
[daviddm-image]: https://david-dm.org/Errorable/order.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/Errorable/order
[coveralls-image]: https://coveralls.io/repos/Errorable/order/badge.svg
[coveralls-url]: https://coveralls.io/r/Errorable/order
