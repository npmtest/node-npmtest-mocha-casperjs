# npmtest-mocha-casperjs

#### basic test coverage for  [mocha-casperjs (v0.6.0)](https://github.com/nathanboktae/mocha-casperjs#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mocha-casperjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mocha-casperjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mocha-casperjs.svg)](https://travis-ci.org/npmtest/node-npmtest-mocha-casperjs)

#### Write CasperJS tests using Mocha

[![NPM](https://nodei.co/npm/mocha-casperjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mocha-casperjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mocha-casperjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mocha-casperjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mocha-casperjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mocha-casperjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mocha-casperjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mocha-casperjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mocha-casperjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mocha-casperjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mocha-casperjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mocha-casperjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mocha-casperjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mocha-casperjs/build/test-report.html](https://npmtest.github.io/node-npmtest-mocha-casperjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mocha-casperjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mocha-casperjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mocha-casperjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mocha-casperjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mocha-casperjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mocha-casperjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mocha-casperjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mocha-casperjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nathan Black"
    },
    "bin": {
        "mocha-casperjs": "./bin/mocha-casperjs"
    },
    "bugs": {
        "url": "http://github.com/nathanboktae/mocha-casperjs/issues"
    },
    "dependencies": {},
    "description": "Write CasperJS tests using Mocha",
    "devDependencies": {
        "casper-chai": ">= 0.1.6",
        "casperjs": "git://github.com/n1k0/casperjs.git#master",
        "chai": "3",
        "coffee-script": "1.7.x",
        "mocha": "2",
        "phantomjs": "^1.9.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "54e95c1a8eb59ee64c2402902e576f651ba38986",
        "tarball": "https://registry.npmjs.org/mocha-casperjs/-/mocha-casperjs-0.6.0.tgz"
    },
    "gitHead": "daac8d158dc17baac174370947a556636fa2f3c1",
    "homepage": "https://github.com/nathanboktae/mocha-casperjs#readme",
    "keywords": [
        "mocha",
        "casperjs",
        "bdd",
        "phantomjs",
        "testing"
    ],
    "license": "MIT",
    "main": "mocha-casperjs.js",
    "maintainers": [
        {
            "name": "nathanboktae"
        }
    ],
    "name": "mocha-casperjs",
    "optionalDependencies": {},
    "peerDependencies": {
        "mocha": ">= 1.14.0",
        "casperjs": ">= 1.1.0-beta3"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nathanboktae/mocha-casperjs.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha test/all.coffee"
    },
    "version": "0.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
