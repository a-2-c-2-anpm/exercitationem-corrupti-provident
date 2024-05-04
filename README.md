# @a-2-c-2-anpm/exercitationem-corrupti-provident <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@a-2-c-2-anpm/exercitationem-corrupti-provident');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@a-2-c-2-anpm/exercitationem-corrupti-provident
[npm-version-svg]: https://versionbadg.es/inspect-js/@a-2-c-2-anpm/exercitationem-corrupti-provident.svg
[deps-svg]: https://david-dm.org/inspect-js/@a-2-c-2-anpm/exercitationem-corrupti-provident.svg
[deps-url]: https://david-dm.org/inspect-js/@a-2-c-2-anpm/exercitationem-corrupti-provident
[dev-deps-svg]: https://david-dm.org/inspect-js/@a-2-c-2-anpm/exercitationem-corrupti-provident/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@a-2-c-2-anpm/exercitationem-corrupti-provident#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@a-2-c-2-anpm/exercitationem-corrupti-provident.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@a-2-c-2-anpm/exercitationem-corrupti-provident.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@a-2-c-2-anpm/exercitationem-corrupti-provident.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@a-2-c-2-anpm/exercitationem-corrupti-provident
[codecov-image]: https://codecov.io/gh/inspect-js/@a-2-c-2-anpm/exercitationem-corrupti-provident/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@a-2-c-2-anpm/exercitationem-corrupti-provident/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@a-2-c-2-anpm/exercitationem-corrupti-provident
[actions-url]: https://github.com/a-2-c-2-anpm/exercitationem-corrupti-provident/actions
