# npmtest-npm-registry

#### basic test coverage for  [npm-registry (v0.1.13)](https://github.com/3rd-Eden/npmjs)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-registry.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-registry) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-registry.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-registry)

#### An high available npm registry client

[![NPM](https://nodei.co/npm/npm-registry.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-registry)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-registry/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-registry/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-registry/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-registry/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-registry/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-npm-registry/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-npm-registry/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-registry/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-registry/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npm-registry/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npm-registry/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-registry/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npm-registry/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npm-registry/build/test-report.html](https://npmtest.github.io/node-npmtest-npm-registry/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm-registry/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm-registry/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npm-registry/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-registry/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-registry/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-registry/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm-registry/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm-registry/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arnout Kazemier"
    },
    "bugs": {
        "url": "https://github.com/3rd-Eden/npmjs/issues"
    },
    "dependencies": {
        "debug": "0.8.x",
        "extract-github": "0.0.x",
        "licenses": "0.0.x",
        "mana": "0.1.x",
        "semver": "2.2.x"
    },
    "description": "An high available npm registry client",
    "devDependencies": {
        "chai": "1.9.x",
        "mocha": "1.18.x",
        "pre-commit": "0.0.x"
    },
    "directories": {},
    "dist": {
        "shasum": "9e5d8b2fdfc1ab5990d47f7debbe231d79a9e822",
        "tarball": "https://registry.npmjs.org/npm-registry/-/npm-registry-0.1.13.tgz"
    },
    "gitHead": "a148ef85a32e5687a141d573d94c9c6d785f1c7e",
    "homepage": "https://github.com/3rd-Eden/npmjs",
    "keywords": [
        "npm",
        "npm-registry",
        "npm-registry-client",
        "npm-ui",
        "npm-www",
        "npm.js",
        "npmjs",
        "registry",
        "registry-client"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jcrugzz"
        },
        {
            "name": "V1"
        },
        {
            "name": "swaagie"
        },
        {
            "name": "indexzero"
        }
    ],
    "name": "npm-registry",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/3rd-Eden/npmjs.git"
    },
    "scripts": {
        "test": "mocha $(find test -name '*.test.js')"
    },
    "version": "0.1.13",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
