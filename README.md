# npmtest-coap

#### basic test coverage for  [coap (v0.21.0)](https://github.com/mcollina/node-coap#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-coap.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-coap) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-coap.svg)](https://travis-ci.org/npmtest/node-npmtest-coap)

#### A CoAP library for node modelled after 'http'

[![NPM](https://nodei.co/npm/coap.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/coap)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-coap/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-coap/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-coap/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-coap/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-coap/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-coap/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-coap/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-coap/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-coap/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-coap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-coap/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-coap/build/test-report.html](https://npmtest.github.io/node-npmtest-coap/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-coap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-coap/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-coap/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-coap/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-coap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-coap/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-coap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-coap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matteo Collina"
    },
    "bugs": {
        "url": "https://github.com/mcollina/node-coap/issues"
    },
    "dependencies": {
        "bl": "^1.0.0",
        "capitalize": "^1.0.0",
        "coap-packet": "^0.1.12",
        "debug": "^2.2.0",
        "fastseries": "^1.7.0",
        "lru-cache": "^4.0.0",
        "readable-stream": "^2.2.2"
    },
    "description": "A CoAP library for node modelled after 'http'",
    "devDependencies": {
        "chai": "^3.4.1",
        "mocha": "^3.2.0",
        "pre-commit": "1.1.3",
        "sinon": "~1.7.3",
        "timekeeper": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ce96f3a80628b2ab543a4a9a64a10679be38261b",
        "tarball": "https://registry.npmjs.org/coap/-/coap-0.21.0.tgz"
    },
    "gitHead": "29f20af1b493e5d296d4d8cf1e6ff406cbd01278",
    "homepage": "https://github.com/mcollina/node-coap#readme",
    "keywords": [
        "coap",
        "m2m",
        "iot",
        "client",
        "server",
        "udp",
        "observe",
        "internet of things",
        "messaging"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "boneskull"
        },
        {
            "name": "giedrius"
        },
        {
            "name": "matteo.collina"
        }
    ],
    "name": "coap",
    "optionalDependencies": {},
    "pre-commit": [
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mcollina/node-coap.git"
    },
    "scripts": {
        "test": "mocha --bail --reporter spec 2>&1",
        "testnobail": "mocha --reporter spec 2>&1"
    },
    "version": "0.21.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
