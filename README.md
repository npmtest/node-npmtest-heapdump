# npmtest-heapdump

#### basic test coverage for  [heapdump (v0.3.9)](https://github.com/bnoordhuis/node-heapdump)  [![npm package](https://img.shields.io/npm/v/npmtest-heapdump.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-heapdump) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-heapdump.svg)](https://travis-ci.org/npmtest/node-npmtest-heapdump)

#### Make a dump of the V8 heap for later inspection.

[![NPM](https://nodei.co/npm/heapdump.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/heapdump)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-heapdump/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-heapdump/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-heapdump/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-heapdump/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-heapdump/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-heapdump/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-heapdump/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-heapdump/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-heapdump/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-heapdump/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-heapdump/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-heapdump/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-heapdump/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-heapdump/build/test-report.html](https://npmtest.github.io/node-npmtest-heapdump/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-heapdump/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-heapdump/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-heapdump/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-heapdump/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-heapdump/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-heapdump/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-heapdump/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-heapdump/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Noordhuis",
        "url": "http://bnoordhuis.nl/"
    },
    "bugs": {
        "url": "https://github.com/bnoordhuis/node-heapdump/issues"
    },
    "dependencies": {},
    "description": "Make a dump of the V8 heap for later inspection.",
    "devDependencies": {
        "shelljs": "~0.3.0",
        "tap": "~0.4.12"
    },
    "directories": {},
    "dist": {
        "shasum": "03c74eb0df5d67be0982e83429ba9c9d2b3b7f78",
        "tarball": "https://registry.npmjs.org/heapdump/-/heapdump-0.3.9.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "7cf17e9b2a629fa5708717874ced2a7ae6cb2e13",
    "gypfile": true,
    "homepage": "https://github.com/bnoordhuis/node-heapdump",
    "license": "ISC",
    "main": "./lib/main",
    "maintainers": [
        {
            "name": "bnoordhuis"
        }
    ],
    "name": "heapdump",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/bnoordhuis/node-heapdump.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "tap test/test-*"
    },
    "version": "0.3.9",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
