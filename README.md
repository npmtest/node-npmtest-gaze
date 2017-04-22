# npmtest-gaze

#### basic test coverage for  [gaze (v1.1.2)](https://github.com/shama/gaze)  [![npm package](https://img.shields.io/npm/v/npmtest-gaze.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gaze) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gaze.svg)](https://travis-ci.org/npmtest/node-npmtest-gaze)

#### A globbing fs.watch wrapper built from the best parts of other fine watch libs.

[![NPM](https://nodei.co/npm/gaze.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gaze)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gaze/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gaze/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gaze/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gaze/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gaze/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gaze/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gaze/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gaze/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gaze/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gaze/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gaze/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gaze/build/test-report.html](https://npmtest.github.io/node-npmtest-gaze/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gaze/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gaze/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gaze/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gaze/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gaze/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gaze/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gaze/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gaze/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kyle Robinson Young"
    },
    "bugs": {
        "url": "https://github.com/shama/gaze/issues"
    },
    "contributors": [
        {
            "name": "Kyle Robinson Young",
            "url": "http://dontkry.com"
        },
        {
            "name": "Sam Day",
            "url": "http://sam.is-super-awesome.com"
        },
        {
            "name": "Roarke Gaskill",
            "url": "http://starkinvestments.com"
        },
        {
            "name": "Lance Pollard",
            "url": "http://lancepollard.com/"
        },
        {
            "name": "Daniel Fagnan",
            "url": "http://hydrocodedesign.com/"
        },
        {
            "name": "Jonas",
            "url": "http://jpommerening.github.io/"
        },
        {
            "name": "Chris Chua",
            "url": "http://sirh.cc/"
        },
        {
            "name": "Kael Zhang",
            "url": "http://kael.me"
        },
        {
            "name": "Krasimir Tsonev",
            "url": "http://krasimirtsonev.com/blog"
        },
        {
            "name": "brett-shwom"
        }
    ],
    "dependencies": {
        "globule": "^1.0.0"
    },
    "description": "A globbing fs.watch wrapper built from the best parts of other fine watch libs.",
    "devDependencies": {
        "async": "^1.5.2",
        "grunt": "^1.0.1",
        "grunt-benchmark": "^0.3.0",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-nodeunit": "^1.0.0",
        "rimraf": "^2.5.2",
        "semistandard": "^7.0.5"
    },
    "directories": {},
    "dist": {
        "shasum": "847224677adb8870d679257ed3388fdb61e40105",
        "tarball": "https://registry.npmjs.org/gaze/-/gaze-1.1.2.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "lib",
        "LICENSE-MIT"
    ],
    "gitHead": "46d6c2afd75b0061e8ec277309b2ab4046b914f1",
    "homepage": "https://github.com/shama/gaze",
    "keywords": [
        "watch",
        "glob"
    ],
    "license": "MIT",
    "main": "lib/gaze",
    "maintainers": [
        {
            "name": "alexgorbatchev"
        },
        {
            "name": "joshperry"
        },
        {
            "name": "shama"
        }
    ],
    "name": "gaze",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/shama/gaze.git"
    },
    "scripts": {
        "test": "semistandard && grunt nodeunit -v"
    },
    "semistandard": {
        "ignore": [
            "benchmarks",
            "experiments",
            "build",
            "test"
        ]
    },
    "version": "1.1.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
