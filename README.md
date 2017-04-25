# npmtest-lynx

#### basic test coverage for  [lynx (v0.2.0)](https://github.com/dscape/lynx)  [![npm package](https://img.shields.io/npm/v/npmtest-lynx.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lynx) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lynx.svg)](https://travis-ci.org/npmtest/node-npmtest-lynx)

#### Minimalistic StatsD client for Node.js programs

[![NPM](https://nodei.co/npm/lynx.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lynx)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lynx/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lynx/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lynx/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lynx/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lynx/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-lynx/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-lynx/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lynx/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lynx/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lynx/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lynx/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lynx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lynx/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lynx/build/test-report.html](https://npmtest.github.io/node-npmtest-lynx/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lynx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lynx/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lynx/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lynx/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lynx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lynx/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lynx/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lynx/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lloyd Hilaiel"
    },
    "bugs": {
        "url": "https://github.com/dscape/lynx/issues"
    },
    "contributors": [
        {
            "name": "Nuno Job",
            "url": "http://nunojob.com"
        },
        {
            "name": "Mark Bogdanoff",
            "url": "https://github.com/bog"
        }
    ],
    "dependencies": {
        "mersenne": "~0.0.3",
        "statsd-parser": "~0.0.4"
    },
    "description": "Minimalistic StatsD client for Node.js programs",
    "devDependencies": {
        "tap": "~0.3.2"
    },
    "directories": {
        "lib": "./lib/"
    },
    "dist": {
        "shasum": "79e6674530da4183e87953bd686171e070da50b9",
        "tarball": "https://registry.npmjs.org/lynx/-/lynx-0.2.0.tgz"
    },
    "homepage": "https://github.com/dscape/lynx",
    "keywords": [
        "stats",
        "metrics",
        "metricsd",
        "statsd",
        "etsy",
        "statsd client",
        "statsd driver",
        "graphite"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/dscape/lynx/raw/master/LICENSE"
        }
    ],
    "main": "./lib/lynx",
    "maintainers": [
        {
            "name": "dscape"
        },
        {
            "name": "lloyd"
        }
    ],
    "name": "lynx",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dscape/lynx.git"
    },
    "scripts": {
        "test": "tap tests/*-test.js"
    },
    "version": "0.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
