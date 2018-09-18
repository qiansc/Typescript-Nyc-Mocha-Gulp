
Typescript-Nyc-Mocha-Gulp
=========================

[![Build Status](https://travis-ci.org/qiansc/Typescript-Nyc-Mocha-Gulp.svg?branch=master)](https://travis-ci.org/node-dmr/dmr-middleware) [![Coveralls](https://img.shields.io/coveralls/qiansc/Typescript-Nyc-Mocha-Gulp.svg)](https://coveralls.io/github/node-dmr/dmr-middleware) [![npm package](https://img.shields.io/npm/v/typescript-nyc-mocha-gulp.svg)](https://www.npmjs.org/package/dmr-middleware) [![npm downloads](http://img.shields.io/npm/dm/typescript-nyc-mocha-gulp.svg)](https://www.npmjs.org/package/dmr-middleware)

Develop
=======

```
# init
npm install

# build
npm run build

# incrementally build
gulp watch
```

Cmd
===

```
# Test
  npm test test/*.ts

  # Cover
  npm run cover

  # TsLint (src/**/*.ts test/**/*.ts)

  # Doc (save to docs/)
  npm doc

  # Readme (save to md/)
  npm md
```

Platform Support
================

\[x\] npm publish & preversion

\[x\] travis

\[x\] coveralls

## Index

### Classes

* [Middleware](classes/middleware.md)

### Interfaces

* [MiddlewareAction](interfaces/middlewareaction.md)
* [MiddlewareOptions](interfaces/middlewareoptions.md)

### Type aliases

* [GatherCallback](#gathercallback)
* [Result](#result)

---

## Type aliases

<a id="gathercallback"></a>

###  GatherCallback

**Ƭ GatherCallback**: *`function`*

*Defined in middleware.ts:41*

#### Type declaration
▸(data?: *[Result](#result)*): `void`

**Parameters:**

| Param | Type |
| ------ | ------ |
| `Optional` data | [Result](#result) |

**Returns:** `void`

___
<a id="result"></a>

###  Result

**Ƭ Result**: *[`string`, `string`]*

*Defined in middleware.ts:37*

___

