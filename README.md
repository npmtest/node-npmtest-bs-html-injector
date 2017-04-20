# npmtest-bs-html-injector

#### basic test coverage for  [bs-html-injector (v3.0.3)](https://github.com/shakyshane/html-injector#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bs-html-injector.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bs-html-injector) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bs-html-injector.svg)](https://travis-ci.org/npmtest/node-npmtest-bs-html-injector)

#### Inject only HTML that has changed.

[![NPM](https://nodei.co/npm/bs-html-injector.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bs-html-injector)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bs-html-injector/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bs-html-injector/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bs-html-injector/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bs-html-injector/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bs-html-injector/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bs-html-injector/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bs-html-injector/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bs-html-injector/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bs-html-injector/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bs-html-injector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bs-html-injector/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bs-html-injector/build/test-report.html](https://npmtest.github.io/node-npmtest-bs-html-injector/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bs-html-injector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bs-html-injector/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bs-html-injector/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bs-html-injector/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bs-html-injector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bs-html-injector/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bs-html-injector/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bs-html-injector/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "browser-sync:ui": {
        "hooks": {
            "markup": "ui/html-injector.html",
            "templates": [
                "ui/html-injector.directive.html"
            ],
            "client:js": [
                "ui/client.js"
            ]
        }
    },
    "bugs": {
        "url": "https://github.com/shakyshane/html-injector/issues"
    },
    "dependencies": {
        "debug": "^2.1.3",
        "dom-compare-temp": "^0.1.0",
        "jsdom": "^6.5.1",
        "request": "^2.40.0"
    },
    "description": "Inject only HTML that has changed.",
    "devDependencies": {
        "browser-sync": "2.12.12",
        "chai": "^3.3.0",
        "lodash-cli": "4.13.1",
        "mocha": "^2.3.3",
        "multiline": "^1.0.2",
        "socket.io-client": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fb3a02f84488c7611842443f6d0cce145fe5b982",
        "tarball": "https://registry.npmjs.org/bs-html-injector/-/bs-html-injector-3.0.3.tgz"
    },
    "files": [
        "lib",
        "lodash.custom.js",
        "ui",
        "index.js",
        "client.js"
    ],
    "gitHead": "3ccc95eb6eee0b2bac4016613780e0b5226f03a1",
    "homepage": "https://github.com/shakyshane/html-injector#readme",
    "keywords": [
        "browser sync plugin",
        "html injection"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "shakyshane"
        }
    ],
    "name": "bs-html-injector",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/shakyshane/html-injector.git"
    },
    "scripts": {
        "lodash": "lodash include=isUndefined,isString,isArray,filter,assign,includes,uniqBy,uniq,without exports=node",
        "test": "mocha --reporter spec"
    },
    "version": "3.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
