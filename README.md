# npmtest-response-time

#### basic test coverage for  [response-time (v2.3.2)](https://github.com/expressjs/response-time)  [![npm package](https://img.shields.io/npm/v/npmtest-response-time.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-response-time) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-response-time.svg)](https://travis-ci.org/npmtest/node-npmtest-response-time)

#### Response time for Node.js servers

[![NPM](https://nodei.co/npm/response-time.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/response-time)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-response-time/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-response-time/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-response-time/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-response-time/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-response-time/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-response-time/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-response-time/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-response-time/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-response-time/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-response-time/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-response-time/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-response-time/build/test-report.html](https://npmtest.github.io/node-npmtest-response-time/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-response-time/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-response-time/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-response-time/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-response-time/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-response-time/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-response-time/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-response-time/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-response-time/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/expressjs/response-time/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        }
    ],
    "dependencies": {
        "depd": "~1.1.0",
        "on-headers": "~1.0.1"
    },
    "description": "Response time for Node.js servers",
    "devDependencies": {
        "after": "0.8.2",
        "eslint": "3.10.1",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-promise": "3.3.2",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ffa71bab952d62f7c1d49b7434355fbc68dffc5a",
        "tarball": "https://registry.npmjs.org/response-time/-/response-time-2.3.2.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "34c40bc97bcd7e54e13b33f77ee231ca2032de6c",
    "homepage": "https://github.com/expressjs/response-time",
    "keywords": [
        "http",
        "res",
        "response time",
        "x-response-time"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "defunctzombie"
        },
        {
            "name": "dougwilson"
        },
        {
            "name": "fishrock123"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "mscdex"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "response-time",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/response-time.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "2.3.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
