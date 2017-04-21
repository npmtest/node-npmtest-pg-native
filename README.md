# npmtest-pg-native

#### basic test coverage for  [pg-native (v1.10.1)](https://github.com/brianc/node-pg-native)  [![npm package](https://img.shields.io/npm/v/npmtest-pg-native.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pg-native) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pg-native.svg)](https://travis-ci.org/npmtest/node-npmtest-pg-native)

#### A slightly nicer interface to Postgres over node-libpq

[![NPM](https://nodei.co/npm/pg-native.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pg-native)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pg-native/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pg-native/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pg-native/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pg-native/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pg-native/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pg-native/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pg-native/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pg-native/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pg-native/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pg-native/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pg-native/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pg-native/build/test-report.html](https://npmtest.github.io/node-npmtest-pg-native/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pg-native/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pg-native/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pg-native/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pg-native/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pg-native/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pg-native/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pg-native/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pg-native/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brian M. Carlson"
    },
    "bugs": {
        "url": "https://github.com/brianc/node-pg-native/issues"
    },
    "dependencies": {
        "libpq": "^1.7.0",
        "pg-types": "1.6.0",
        "readable-stream": "1.0.31"
    },
    "description": "A slightly nicer interface to Postgres over node-libpq",
    "devDependencies": {
        "async": "^0.9.0",
        "concat-stream": "^1.4.6",
        "generic-pool": "^2.1.1",
        "lodash": "^2.4.1",
        "mocha": "^1.21.4",
        "okay": "^0.3.0",
        "pg": "*",
        "semver": "^4.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "94e61ccbb85a7f3436b2e526315c7581107fe40c",
        "tarball": "https://registry.npmjs.org/pg-native/-/pg-native-1.10.1.tgz"
    },
    "gitHead": "e45f2d18a64ac61d61166a21f1b3a81639e88d2c",
    "homepage": "https://github.com/brianc/node-pg-native",
    "keywords": [
        "postgres",
        "pg",
        "libpq"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "brianc"
        }
    ],
    "name": "pg-native",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/brianc/node-pg-native.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "1.10.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
