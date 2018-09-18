
Typescript-Nyc-Mocha-Gulp
=========================

[![Build Status](https://travis-ci.org/qiansc/Typescript-Nyc-Mocha-Gulp.svg?branch=master)](https://travis-ci.org/qiansc/Typescript-Nyc-Mocha-Gulp) [![Coveralls](https://img.shields.io/coveralls/qiansc/Typescript-Nyc-Mocha-Gulp.svg)](https://coveralls.io/github/qiansc/Typescript-Nyc-Mocha-Gulp) [![npm package](https://img.shields.io/npm/v/typescript-nyc-mocha-gulp.svg)](https://www.npmjs.org/package/typescript-nyc-mocha-gulp) [![npm downloads](http://img.shields.io/npm/dm/typescript-nyc-mocha-gulp.svg)](https://www.npmjs.org/package/typescript-nyc-mocha-gulp)

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

*    preversion before npm publish
    *   tslint
    *   cover

*   [Travis](https://github.com/qiansc/Typescript-Nyc-Mocha-Gulp/blob/master/.travis.yml) [![Build Status](https://travis-ci.org/qiansc/Typescript-Nyc-Mocha-Gulp.svg?branch=master)](https://travis-ci.org/qiansc/Typescript-Nyc-Mocha-Gulp)
    
*   Coveralls [![Coveralls](https://img.shields.io/coveralls/qiansc/Typescript-Nyc-Mocha-Gulp.svg)](https://coveralls.io/github/qiansc/Typescript-Nyc-Mocha-Gulp)

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

*Defined in [middleware.ts:41](https://github.com/qiansc/Typescript-Nyc-Mocha-Gulp/blob/f011cd6/src/middleware.ts#L41)*

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

*Defined in [middleware.ts:37](https://github.com/qiansc/Typescript-Nyc-Mocha-Gulp/blob/f011cd6/src/middleware.ts#L37)*

___

