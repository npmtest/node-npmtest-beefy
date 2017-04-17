# test coverage for  [beefy (v2.1.8)](https://github.com/chrisdickinson/beefy#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-beefy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-beefy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-beefy.svg)](https://travis-ci.org/npmtest/node-npmtest-beefy)
#### local development server that aims to make using browserify fast and fun

[![NPM](https://nodei.co/npm/beefy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/beefy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-beefy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-beefy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-beefy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-beefy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-beefy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-beefy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-beefy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-beefy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-beefy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-beefy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-beefy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-beefy/build/test-report.html](https://npmtest.github.io/node-npmtest-beefy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-beefy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-beefy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-beefy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-beefy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-beefy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-beefy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-beefy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-beefy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Chris Dickinson"
    },
    "bin": {
        "beefy": "./bin/beefy"
    },
    "bugs": {
        "url": "https://github.com/chrisdickinson/beefy/issues"
    },
    "dependencies": {
        "ansicolors": "~0.3.2",
        "chokidar": "^1.0.0",
        "concat-stream": "^1.4.3",
        "find-global-packages": "0.0.1",
        "ignorepatterns": "^1.0.1",
        "leftpad": "0.0.0",
        "mime": "~1.2.9",
        "minimist": "0.0.8",
        "open": "0.0.3",
        "portfinder": "~0.2.1",
        "pretty-bytes": "~0.1.0",
        "readable-stream": "^1.0.27-1",
        "resolve": "^0.6.1",
        "response-stream": "0.0.0",
        "script-injector": "~1.0.0",
        "through": "~2.2.0",
        "which": "~1.0.5",
        "xtend": "~2.1.2"
    },
    "description": "local development server that aims to make using browserify fast and fun",
    "devDependencies": {
        "browserify": "^3.32.1",
        "dotpathlookup": "0.0.1",
        "istanbul": "^0.2.8",
        "jsl": "^0.1.3",
        "mock": "^0.1.1",
        "tape": "~2.10.2",
        "touch": "0.0.3",
        "watchify": "^0.10.2"
    },
    "directories": {},
    "dist": {
        "shasum": "7bc11b9a487a9a34679d85e29d3b52f374fd0029",
        "tarball": "https://registry.npmjs.org/beefy/-/beefy-2.1.8.tgz"
    },
    "gitHead": "7a4727851c3c318d8a866d14c4c2f9b93a064b08",
    "homepage": "https://github.com/chrisdickinson/beefy#readme",
    "keywords": [
        "simplehttpserver",
        "browserify"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "chrisdickinson"
        },
        {
            "name": "dlmanning"
        }
    ],
    "name": "beefy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/chrisdickinson/beefy.git"
    },
    "scripts": {
        "test": "node test",
        "test-cov": "istanbul cover test/index.js"
    },
    "version": "2.1.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
