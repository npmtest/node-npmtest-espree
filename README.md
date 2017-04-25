# npmtest-espree

#### basic test coverage for  [espree (v3.4.2)](https://github.com/eslint/espree)  [![npm package](https://img.shields.io/npm/v/npmtest-espree.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-espree) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-espree.svg)](https://travis-ci.org/npmtest/node-npmtest-espree)

#### An Esprima-compatible JavaScript parser built on Acorn

[![NPM](https://nodei.co/npm/espree.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/espree)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-espree/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-espree/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-espree/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-espree/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-espree/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-espree/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-espree/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-espree/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-espree/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-espree/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-espree/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-espree/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-espree/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-espree/build/test-report.html](https://npmtest.github.io/node-npmtest-espree/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-espree/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-espree/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-espree/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-espree/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-espree/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-espree/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-espree/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-espree/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicholas C. Zakas"
    },
    "bugs": {
        "url": "http://github.com/eslint/espree.git"
    },
    "dependencies": {
        "acorn": "^5.0.1",
        "acorn-jsx": "^3.0.0"
    },
    "description": "An Esprima-compatible JavaScript parser built on Acorn",
    "devDependencies": {
        "browserify": "^7.0.0",
        "chai": "^1.10.0",
        "eslint": "^2.13.1",
        "eslint-config-eslint": "^3.0.0",
        "eslint-release": "^0.10.0",
        "esprima": "latest",
        "esprima-fb": "^8001.2001.0-dev-harmony-fb",
        "istanbul": "~0.2.6",
        "json-diff": "~0.3.1",
        "leche": "^1.0.1",
        "mocha": "^2.0.1",
        "regenerate": "~0.5.4",
        "shelljs": "^0.3.0",
        "shelljs-nodecli": "^0.1.1",
        "unicode-6.3.0": "~0.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "38dbdedbedc95b8961a1fbf04734a8f6a9c8c592",
        "tarball": "https://registry.npmjs.org/espree/-/espree-3.4.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "lib",
        "espree.js"
    ],
    "gitHead": "b9140c37d50764c6a89020918646461f327f3301",
    "homepage": "https://github.com/eslint/espree",
    "keywords": [
        "ast",
        "ecmascript",
        "javascript",
        "parser",
        "syntax",
        "acorn"
    ],
    "license": "BSD-2-Clause",
    "main": "espree.js",
    "maintainers": [
        {
            "name": "btmills"
        },
        {
            "name": "eslint"
        },
        {
            "name": "gyandeeps"
        },
        {
            "name": "ivolodin"
        },
        {
            "name": "kaicataldo"
        },
        {
            "name": "mysticatea"
        },
        {
            "name": "not-an-aardvark"
        },
        {
            "name": "nzakas"
        },
        {
            "name": "sharpbites"
        }
    ],
    "name": "espree",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/eslint/espree.git"
    },
    "scripts": {
        "alpharelease": "eslint-prelease alpha",
        "betarelease": "eslint-prelease beta",
        "browserify": "node Makefile.js browserify",
        "ci-release": "eslint-ci-release",
        "generate-regex": "node tools/generate-identifier-regex.js",
        "gh-release": "eslint-gh-release",
        "lint": "node Makefile.js lint",
        "release": "eslint-release",
        "test": "npm run-script lint && node Makefile.js test"
    },
    "version": "3.4.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
