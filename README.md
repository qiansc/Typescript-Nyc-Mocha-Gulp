# Typescript-Nyc-Mocha-Gulp
[![Build Status](https://travis-ci.org/qiansc/Typescript-Nyc-Mocha-Gulp.svg?branch=master)](https://travis-ci.org/qiansc/Typescript-Nyc-Mocha-Gulp)
[![Coveralls](https://img.shields.io/coveralls/qiansc/Typescript-Nyc-Mocha-Gulp.svg)](https://coveralls.io/github/qiansc/Typescript-Nyc-Mocha-Gulp)
[![npm package](https://img.shields.io/npm/v/typescript-nyc-mocha-gulp.svg)](https://www.npmjs.org/package/typescript-nyc-mocha-gulp)
[![npm downloads](http://img.shields.io/npm/dm/typescript-nyc-mocha-gulp.svg)](https://www.npmjs.org/package/typescript-nyc-mocha-gulp)

A Project With:

- TypeScript ^3.0
- Travis Nyc(coveralls)
- Mocha(based TS) Gulp-typescript
- TsLint TsDoc

# Develop

Project

```
# init
npm install

# build
npm run build

# incrementally build
gulp watch

```

Global (optional)

```
npm install gulp -g
npm install typescript -g
```

# Cmd

```
  # Test 本地TS测试
  npm test test/*.ts

  # Cover 覆盖率检查
  npm run cover

  # TsLint (src/**/*.ts test/**/*.ts) 语法检查
  npm run lint

  # Doc (save to docs/) 生成html api 文档
  npm doc

  # Readme (save to md/) 生成MD 文档
  npm md

```

# Platform Support

- [x] preversion before npm publish
  - tslint
  - cover


- [x] [Travis](https://github.com/qiansc/Typescript-Nyc-Mocha-Gulp/blob/master/.travis.yml) [![Build Status](https://travis-ci.org/qiansc/Typescript-Nyc-Mocha-Gulp.svg?branch=master)](https://travis-ci.org/qiansc/Typescript-Nyc-Mocha-Gulp)

- [x] Coveralls [![Coveralls](https://img.shields.io/coveralls/qiansc/Typescript-Nyc-Mocha-Gulp.svg)](https://coveralls.io/github/qiansc/Typescript-Nyc-Mocha-Gulp)
