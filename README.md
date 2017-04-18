# npmtest-read-package-json

#### test coverage for  [read-package-json (v2.0.5)](https://github.com/npm/read-package-json#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-read-package-json.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-read-package-json) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-read-package-json.svg)](https://travis-ci.org/npmtest/node-npmtest-read-package-json)

#### The thing npm uses to read package.json files with semantics and defaults and validation

[![NPM](https://nodei.co/npm/read-package-json.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/read-package-json)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-read-package-json/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-read-package-json/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-read-package-json/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-read-package-json/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-read-package-json/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-read-package-json/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-read-package-json/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-read-package-json/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-read-package-json/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-read-package-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-read-package-json/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-read-package-json/build/test-report.html](https://npmtest.github.io/node-npmtest-read-package-json/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-read-package-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-read-package-json/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-read-package-json/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-read-package-json/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-read-package-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-read-package-json/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-read-package-json/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-read-package-json/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter",
        "url": "http://blog.izs.me/"
    },
    "bugs": {
        "url": "https://github.com/npm/read-package-json/issues"
    },
    "dependencies": {
        "glob": "^7.1.1",
        "graceful-fs": "^4.1.2",
        "json-parse-helpfulerror": "^1.0.2",
        "normalize-package-data": "^2.0.0"
    },
    "description": "The thing npm uses to read package.json files with semantics and defaults and validation",
    "devDependencies": {
        "standard": "^9.0.1",
        "tap": "^10.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f93a64e641529df68a08c64de46389e8a3f88845",
        "tarball": "https://registry.npmjs.org/read-package-json/-/read-package-json-2.0.5.tgz"
    },
    "gitHead": "0b03bd75bda0540de4102b543b94ccaf3fb7c034",
    "homepage": "https://github.com/npm/read-package-json#readme",
    "license": "ISC",
    "main": "read-json.js",
    "maintainers": [
        {
            "name": "iarna"
        },
        {
            "name": "isaacs"
        },
        {
            "name": "othiym23"
        },
        {
            "name": "zkat"
        }
    ],
    "name": "read-package-json",
    "optionalDependencies": {
        "graceful-fs": "^4.1.2"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/npm/read-package-json.git"
    },
    "scripts": {
        "test": "standard && tap -J test/*.js"
    },
    "version": "2.0.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
