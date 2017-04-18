# npmtest-koala

#### test coverage for  [koala (v1.0.0)](https://github.com/koajs/koala#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-koala.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koala) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koala.svg)](https://travis-ci.org/npmtest/node-npmtest-koala)

#### Koa Framework Suite

[![NPM](https://nodei.co/npm/koala.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koala)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koala/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koala/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koala/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koala/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koala/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koala/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koala/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koala/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koala/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koala/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koala/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koala/build/test-report.html](https://npmtest.github.io/node-npmtest-koala/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koala/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koala/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koala/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koala/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koala/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koala/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koala/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koala/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/koajs/koala/issues"
    },
    "dependencies": {
        "basic-auth": "1",
        "bluebird": "2",
        "commander": "2",
        "debug": "*",
        "delegates": "0",
        "koa": "0",
        "koa-body-parsers": "^1.1.0",
        "koa-cash": "1",
        "koa-compress": "1",
        "koa-csrf": "2",
        "koa-error": "1",
        "koa-etag": "2",
        "koa-file-server": "2",
        "koa-json": "1",
        "koa-logger": "1",
        "koa-qs": "^2.0.0",
        "koa-response-time": "1",
        "koa-safe-jsonp": "0",
        "koa-session": "^3.2.0",
        "koa-trace": "1",
        "merge-descriptors": "^1.0.0",
        "ms": "0",
        "mz": "^2.0.0",
        "qs": ">= 2"
    },
    "description": "Koa Framework Suite",
    "devDependencies": {
        "istanbul-harmony": "0",
        "mocha": "2",
        "supertest": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "abac8f32dbf60dc4102ce6b13a997f66f6ffdcbf",
        "tarball": "https://registry.npmjs.org/koala/-/koala-1.0.0.tgz"
    },
    "files": [
        "lib",
        "bin",
        "docs",
        "template"
    ],
    "gitHead": "9ad2a394f8af9cda0c5a6b56202ec2e3dae283d5",
    "homepage": "https://github.com/koajs/koala#readme",
    "keywords": [
        "koa",
        "http",
        "https",
        "http2",
        "framework",
        "generators",
        "es6",
        "modules",
        "promises",
        "push"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "aheckmann"
        }
    ],
    "name": "koala",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/koajs/koala.git"
    },
    "scripts": {
        "test": "NODE_ENV=test mocha --reporter spec --timeout 30s --bail test/app/index.js",
        "test-cov": "NODE_ENV=test node node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --reporter dot --timeout 2m --bail test/app/index.js",
        "test-travis": "NODE_ENV=test node node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- --reporter dot --timeout 2m --bail test/app/index.js"
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
