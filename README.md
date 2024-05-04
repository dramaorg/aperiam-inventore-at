# @dramaorg/aperiam-inventore-at <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@dramaorg/aperiam-inventore-at');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@dramaorg/aperiam-inventore-at
[npm-version-svg]: https://versionbadg.es/inspect-js/@dramaorg/aperiam-inventore-at.svg
[deps-svg]: https://david-dm.org/inspect-js/@dramaorg/aperiam-inventore-at.svg
[deps-url]: https://david-dm.org/inspect-js/@dramaorg/aperiam-inventore-at
[dev-deps-svg]: https://david-dm.org/inspect-js/@dramaorg/aperiam-inventore-at/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@dramaorg/aperiam-inventore-at#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@dramaorg/aperiam-inventore-at.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@dramaorg/aperiam-inventore-at.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@dramaorg/aperiam-inventore-at.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@dramaorg/aperiam-inventore-at
[codecov-image]: https://codecov.io/gh/inspect-js/@dramaorg/aperiam-inventore-at/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@dramaorg/aperiam-inventore-at/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@dramaorg/aperiam-inventore-at
[actions-url]: https://github.com/dramaorg/aperiam-inventore-at/actions
