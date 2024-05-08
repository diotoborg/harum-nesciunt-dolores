# @diotoborg/harum-nesciunt-dolores <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A helper to optimistically set Symbol.toStringTag, when possible.

Most common usage:
```js
var assert = require('assert');
var setToStringTag = require('@diotoborg/harum-nesciunt-dolores');

var obj = {};

assert.equal(Object.prototype.toString.call(obj), '[object Object]');

setToStringTag(obj, 'tagged!');

assert.equal(Object.prototype.toString.call(obj), '[object tagged!]');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.com/package/@diotoborg/harum-nesciunt-dolores
[npm-version-svg]: https://versionbadg.es/es-shims/@diotoborg/harum-nesciunt-dolores.svg
[deps-svg]: https://david-dm.org/es-shims/@diotoborg/harum-nesciunt-dolores.svg
[deps-url]: https://david-dm.org/es-shims/@diotoborg/harum-nesciunt-dolores
[dev-deps-svg]: https://david-dm.org/es-shims/@diotoborg/harum-nesciunt-dolores/dev-status.svg
[dev-deps-url]: https://david-dm.org/es-shims/@diotoborg/harum-nesciunt-dolores#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@diotoborg/harum-nesciunt-dolores.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@diotoborg/harum-nesciunt-dolores.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@diotoborg/harum-nesciunt-dolores.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@diotoborg/harum-nesciunt-dolores
[codecov-image]: https://codecov.io/gh/es-shims/@diotoborg/harum-nesciunt-dolores/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/es-shims/@diotoborg/harum-nesciunt-dolores/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/es-shims/@diotoborg/harum-nesciunt-dolores
[actions-url]: https://github.com/diotoborg/harum-nesciunt-dolores/actions
