# npmtest-x-ray

#### basic test coverage for  [x-ray (v2.3.2)](https://github.com/lapwinglabs/x-ray#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-x-ray.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-x-ray) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-x-ray.svg)](https://travis-ci.org/npmtest/node-npmtest-x-ray)

#### structure any website

[![NPM](https://nodei.co/npm/x-ray.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/x-ray)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-x-ray/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-x-ray/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-x-ray/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-x-ray/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-x-ray/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-x-ray/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-x-ray/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-x-ray/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-x-ray/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-x-ray/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-x-ray/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-x-ray/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-x-ray/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-x-ray/build/test-report.html](https://npmtest.github.io/node-npmtest-x-ray/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-x-ray/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-x-ray/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-x-ray/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-x-ray/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-x-ray/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-x-ray/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-x-ray/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-x-ray/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matthew Mueller"
    },
    "bugs": {
        "url": "https://github.com/lapwinglabs/x-ray/issues"
    },
    "contributors": [
        {
            "name": "Fabien Franzen"
        }
    ],
    "dependencies": {
        "batch": "~0.5.2",
        "chalk": "~1.1.1",
        "cheerio": "~0.20.0",
        "debug": "~2.2.0",
        "enstore": "~1.0.1",
        "is-url": "~1.2.0",
        "isobject": "~2.0.0",
        "object-assign": "~4.0.1",
        "x-ray-crawler": "~2.0.1",
        "x-ray-parse": "~1.0.1"
    },
    "description": "structure any website",
    "devDependencies": {
        "concat-stream": "~1.5.1",
        "coveralls": "~2.11.8",
        "istanbul": "~0.4.2",
        "mocha": "latest",
        "mocha-lcov-reporter": "~1.2.0",
        "multiline": "~1.0.2",
        "rimraf": "~2.5.2",
        "standard": "~6.0.8"
    },
    "directories": {},
    "dist": {
        "shasum": "5d1ecc84b48a01ebea73f70a6fa0d1171bbc39e4",
        "tarball": "https://registry.npmjs.org/x-ray/-/x-ray-2.3.2.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "gitHead": "d9996bc9166905c3a44256c976ec9184800f1c45",
    "homepage": "https://github.com/lapwinglabs/x-ray#readme",
    "keywords": [
        "api",
        "cheerio",
        "scrape",
        "scraper",
        "structure",
        "web"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "kikobeats"
        },
        {
            "name": "mattmueller"
        }
    ],
    "name": "x-ray",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/lapwinglabs/x-ray.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/.bin/_mocha --report lcovonly",
        "pretest": "standard",
        "test": "mocha"
    },
    "version": "2.3.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
