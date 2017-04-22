# npmtest-up

#### basic test coverage for  [up (v0.7.0)](https://github.com/Automattic/cloudup-cli#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-up.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-up) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-up.svg)](https://travis-ci.org/npmtest/node-npmtest-up)

#### cloudup command-line executable

[![NPM](https://nodei.co/npm/up.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/up)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-up/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-up/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-up/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-up/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-up/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-up/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-up/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-up/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-up/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-up/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-up/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-up/build/test-report.html](https://npmtest.github.io/node-npmtest-up/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-up/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-up/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-up/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-up/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-up/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-up/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-up/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-up/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "up": "bin/up",
        "up-streams": "bin/up-streams",
        "up-config": "bin/up-config",
        "up-copy": "bin/up-copy",
        "up-open": "bin/up-open"
    },
    "bugs": {
        "url": "https://github.com/Automattic/cloudup-cli/issues"
    },
    "dependencies": {
        "ansi": "~0.3.0",
        "bytes": "~2.1.0",
        "cliparoo": "1.0.0",
        "cloudup-client": "0.3.2",
        "co": "3.1.0",
        "co-prompt": "1.0.0",
        "commander": "1.3.2",
        "gnode": "0.1.1",
        "head": "~1.0.0",
        "is-code": "~1.1.0",
        "max-component": "~1.0.0",
        "ms": "0.7.1",
        "open": "0.0.5",
        "osenv": "~0.1.1",
        "osthumb": "0.0.1",
        "printf": "0.2.2",
        "sum-component": "~0.1.1",
        "term-list": "0.2.1",
        "thunkify": "2.1.2",
        "uid2": "0.0.3"
    },
    "description": "cloudup command-line executable",
    "devDependencies": {
        "better-assert": "*",
        "mocha": "*",
        "should": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "3bd928e781313ce332d142eb6f43782dc24d2257",
        "tarball": "https://registry.npmjs.org/up/-/up-0.7.0.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "7c414a2b53c08ac2ab5a6b98c2f072deae0ff1bd",
    "homepage": "https://github.com/Automattic/cloudup-cli#readme",
    "keywords": [
        "cloudup",
        "upload",
        "file",
        "files",
        "cli"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "rauchg"
        },
        {
            "name": "tootallnate"
        }
    ],
    "name": "up",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/Automattic/cloudup-cli.git"
    },
    "scripts": {},
    "version": "0.7.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
