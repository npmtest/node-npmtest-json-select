# npmtest-json-select

#### basic test coverage for  [json-select (v2.2.0)](https://github.com/dominictarr/json-select)  [![npm package](https://img.shields.io/npm/v/npmtest-json-select.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-json-select) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-json-select.svg)](https://travis-ci.org/npmtest/node-npmtest-json-select)

#### select json from (very large) json files

[![NPM](https://nodei.co/npm/json-select.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/json-select)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-json-select/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-json-select/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-json-select/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-json-select/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-json-select/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-json-select/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-json-select/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-json-select/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-json-select/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-json-select/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-json-select/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-json-select/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-json-select/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-json-select/build/test-report.html](https://npmtest.github.io/node-npmtest-json-select/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-json-select/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-json-select/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-json-select/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-json-select/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-json-select/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-json-select/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-json-select/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-json-select/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dominic Tarr",
        "url": "dominictarr.com"
    },
    "bin": {
        "json-select": "./index.js"
    },
    "bugs": {
        "url": "https://github.com/dominictarr/json-select/issues"
    },
    "dependencies": {
        "JSONStream": "~0.8.0"
    },
    "description": "select json from (very large) json files",
    "devDependencies": {
        "tape": "~2.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "c72f9ee775110faf62bd31f5e9cb1e793b98c5e6",
        "tarball": "https://registry.npmjs.org/json-select/-/json-select-2.2.0.tgz"
    },
    "homepage": "https://github.com/dominictarr/json-select",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dominictarr"
        }
    ],
    "name": "json-select",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dominictarr/json-select.git"
    },
    "scripts": {
        "test": "set -e; for t in test/*.js; do node $t; done"
    },
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
