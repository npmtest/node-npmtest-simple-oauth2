# test coverage for  [simple-oauth2 (v1.1.0)](https://github.com/lelylan/simple-oauth2)  [![npm package](https://img.shields.io/npm/v/npmtest-simple-oauth2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-simple-oauth2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-simple-oauth2.svg)](https://travis-ci.org/npmtest/node-npmtest-simple-oauth2)
#### Node.js client for OAuth2

[![NPM](https://nodei.co/npm/simple-oauth2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/simple-oauth2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-simple-oauth2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-simple-oauth2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-simple-oauth2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-simple-oauth2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-simple-oauth2/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-simple-oauth2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-simple-oauth2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-simple-oauth2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-simple-oauth2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-simple-oauth2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-simple-oauth2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-simple-oauth2/build/test-report.html](https://npmtest.github.io/node-npmtest-simple-oauth2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-simple-oauth2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-simple-oauth2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-simple-oauth2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-simple-oauth2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-simple-oauth2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-simple-oauth2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-simple-oauth2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-simple-oauth2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrea Reginato"
    },
    "bugs": {
        "url": "https://github.com/lelylan/simple-oauth2/issues"
    },
    "contributors": [
        {
            "name": "Jonathan Samines"
        }
    ],
    "dependencies": {
        "bluebird": "^2.10.1",
        "date-fns": "^1.3.0",
        "debug": "^2.2.0",
        "joi": "^9.0.4",
        "request": "^2.67.0"
    },
    "description": "Node.js client for OAuth2",
    "devDependencies": {
        "chai": "^3.5.0",
        "doctoc": "^1.0.0",
        "eslint": "^3.2.2",
        "eslint-config-airbnb-base": "^5.0.1",
        "eslint-plugin-import": "^1.12.0",
        "mocha": "^3.0.0",
        "nock": "^8.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1cea8793ed91b378e124e6d32173f194bd1522a1",
        "tarball": "https://registry.npmjs.org/simple-oauth2/-/simple-oauth2-1.1.0.tgz"
    },
    "engine": {
        "node": ">=4.0"
    },
    "gitHead": "a5ed92450ed5316b9c3924861aa76b142a61e71b",
    "homepage": "https://github.com/lelylan/simple-oauth2",
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "andreareginato"
        },
        {
            "name": "jonathansamines"
        }
    ],
    "name": "simple-oauth2",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lelylan/simple-oauth2.git"
    },
    "scripts": {
        "docs-gen": "doctoc README.md --github --no-title",
        "format": "eslint . --fix",
        "lint": "eslint .",
        "pretest": "npm run lint",
        "test": "mocha ",
        "test-watch": "mocha --watch --reporter=spec"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
