# npmtest-tio2

#### basic test coverage for  tio2 (v0.2.3)  [![npm package](https://img.shields.io/npm/v/npmtest-tio2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tio2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tio2.svg)](https://travis-ci.org/npmtest/node-npmtest-tio2)

#### Developer testing for Titanium

[![NPM](https://nodei.co/npm/tio2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tio2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tio2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tio2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tio2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tio2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tio2/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tio2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tio2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tio2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tio2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tio2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tio2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tio2/build/test-report.html](https://npmtest.github.io/node-npmtest-tio2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tio2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tio2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tio2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tio2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tio2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tio2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tio2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tio2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "tio2",
    "version": "0.2.3",
    "description": "Developer testing for Titanium",
    "keywords": [
        "titanium",
        "automation",
        "android",
        "iphone",
        "ios",
        "hyperloop"
    ],
    "author": {
        "name": "Appcelerator, Inc."
    },
    "maintainers": [
        {
            "name": "Jeff Haynie"
        },
        {
            "name": "Chris Barber"
        }
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/appcelerator/tio2.git"
    },
    "ingot": {
        "type": "plugin",
        "api": "1.0"
    },
    "license": "Apache Public License v2",
    "main": "index.js",
    "bin": "./bin/tio2",
    "bugs": {
        "url": "https://github.com/appcelerator/tio2/issues"
    },
    "dependencies": {
        "androidlib": "~0.1.7",
        "async": "~0.9.0",
        "cli-table": "~0.3.0",
        "colors": "~0.6.2",
        "commander": "~2.3.0",
        "ejs": "~1.0.0",
        "ioslib": "~0.2.9",
        "longjohn": "~0.2.4",
        "node-appc": "~0.2.17",
        "should": "~4.0.4",
        "source-map": "~0.1.39",
        "sprintf": "~0.1.4",
        "temp": "~0.8.1",
        "ti-mocha": "~0.1.3",
        "tiapp.xml": "~0.2.0",
        "uglify-js": "~2.4.15",
        "winston": "~0.8.0",
        "wrench": "~1.5.8"
    },
    "scripts": {
        "test": "npm test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
