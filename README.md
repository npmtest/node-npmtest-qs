# npmtest-qs

#### basic test coverage for  [qs (v6.4.0)](https://github.com/ljharb/qs)  [![npm package](https://img.shields.io/npm/v/npmtest-qs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-qs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-qs.svg)](https://travis-ci.org/npmtest/node-npmtest-qs)

#### A querystring parser that supports nesting and arrays, with a depth limit

[![NPM](https://nodei.co/npm/qs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/qs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-qs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-qs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-qs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-qs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-qs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-qs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-qs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-qs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-qs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-qs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-qs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-qs/build/test-report.html](https://npmtest.github.io/node-npmtest-qs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-qs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-qs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-qs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-qs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-qs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-qs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-qs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-qs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/ljharb/qs/issues"
    },
    "contributors": [
        {
            "name": "Jordan Harband",
            "url": "http://ljharb.codes"
        }
    ],
    "dependencies": {},
    "description": "A querystring parser that supports nesting and arrays, with a depth limit",
    "devDependencies": {
        "@ljharb/eslint-config": "^11.0.0",
        "browserify": "^14.1.0",
        "covert": "^1.1.0",
        "eslint": "^3.17.0",
        "evalmd": "^0.0.17",
        "iconv-lite": "^0.4.15",
        "mkdirp": "^0.5.1",
        "parallelshell": "^2.0.0",
        "qs-iconv": "^1.0.4",
        "safe-publish-latest": "^1.1.1",
        "tape": "^4.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "13e26d28ad6b0ffaa91312cd3bf708ed351e7233",
        "tarball": "https://registry.npmjs.org/qs/-/qs-6.4.0.tgz"
    },
    "engines": {
        "node": ">=0.6"
    },
    "gitHead": "c7f87b8d2eedd377f6ace065655201f51bee6334",
    "homepage": "https://github.com/ljharb/qs",
    "keywords": [
        "querystring",
        "qs"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "ljharb"
        },
        {
            "name": "nlf"
        }
    ],
    "name": "qs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ljharb/qs.git"
    },
    "scripts": {
        "coverage": "covert test",
        "dist": "mkdirp dist && browserify --standalone Qs lib/index.js > dist/qs.js",
        "lint": "eslint lib/*.js test/*.js",
        "prepublish": "safe-publish-latest && npm run dist",
        "pretest": "npm run --silent readme && npm run --silent lint",
        "readme": "evalmd README.md",
        "test": "npm run --silent coverage",
        "tests-only": "node test"
    },
    "version": "6.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
