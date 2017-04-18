# npmtest-factor-bundle

#### test coverage for  [factor-bundle (v2.5.0)](https://github.com/substack/factor-bundle)  [![npm package](https://img.shields.io/npm/v/npmtest-factor-bundle.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-factor-bundle) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-factor-bundle.svg)](https://travis-ci.org/npmtest/node-npmtest-factor-bundle)

#### factor browser-pack bundles into common shared bundles

[![NPM](https://nodei.co/npm/factor-bundle.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/factor-bundle)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-factor-bundle/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-factor-bundle/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-factor-bundle/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-factor-bundle/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-factor-bundle/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-factor-bundle/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-factor-bundle/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-factor-bundle/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-factor-bundle/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-factor-bundle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-factor-bundle/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-factor-bundle/build/test-report.html](https://npmtest.github.io/node-npmtest-factor-bundle/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-factor-bundle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-factor-bundle/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-factor-bundle/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-factor-bundle/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-factor-bundle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-factor-bundle/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-factor-bundle/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-factor-bundle/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bin": {
        "factor-bundle": "bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/substack/factor-bundle/issues"
    },
    "dependencies": {
        "JSONStream": "~0.8.4",
        "browser-pack": "^5.0.1",
        "defined": "0.0.0",
        "deps-topo-sort": "~0.2.1",
        "inherits": "^2.0.1",
        "isarray": "0.0.1",
        "labeled-stream-splicer": "^1.0.0",
        "minimist": "~0.2.0",
        "nub": "0.0.0",
        "outpipe": "^1.1.0",
        "reversepoint": "~0.2.0",
        "stream-combiner": "~0.2.1",
        "through2": "^0.5.1",
        "xtend": "^4.0.0"
    },
    "description": "factor browser-pack bundles into common shared bundles",
    "devDependencies": {
        "browser-unpack": "^1.1.1",
        "browserify": "^11.0.1",
        "concat-stream": "^1.4.6",
        "mkdirp": "~0.5.0",
        "module-deps": "^3.9.0",
        "osenv": "^0.1.0",
        "tape": "^4.0.1",
        "through": "^2.3.4"
    },
    "directories": {},
    "dist": {
        "shasum": "8ea8957da39d7586283cc3ee353cd9911a45e779",
        "tarball": "https://registry.npmjs.org/factor-bundle/-/factor-bundle-2.5.0.tgz"
    },
    "gitHead": "ee80ac45642dfcf5ee1f6048a1e7a2be72e85e3a",
    "homepage": "https://github.com/substack/factor-bundle",
    "keywords": [
        "browser-pack",
        "browserify",
        "browserify-plugin",
        "browserify-tool",
        "bundle"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack"
        },
        {
            "name": "terinjokes"
        }
    ],
    "name": "factor-bundle",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/factor-bundle.git"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "version": "2.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
