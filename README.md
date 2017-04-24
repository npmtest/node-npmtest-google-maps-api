# npmtest-google-maps-api

#### basic test coverage for  [google-maps-api (v2.0.1)](https://github.com/Jam3/google-maps-api)  [![npm package](https://img.shields.io/npm/v/npmtest-google-maps-api.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-google-maps-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-google-maps-api.svg)](https://travis-ci.org/npmtest/node-npmtest-google-maps-api)

#### Get up and running with the google maps API quickly

[![NPM](https://nodei.co/npm/google-maps-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/google-maps-api)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-google-maps-api/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-maps-api/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-google-maps-api/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-google-maps-api/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-google-maps-api/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-google-maps-api/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-google-maps-api/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-google-maps-api/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-google-maps-api/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-google-maps-api/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-google-maps-api/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-maps-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-google-maps-api/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-google-maps-api/build/test-report.html](https://npmtest.github.io/node-npmtest-google-maps-api/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-google-maps-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-google-maps-api/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-google-maps-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-google-maps-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-google-maps-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-google-maps-api/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-google-maps-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-google-maps-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "google-maps-api",
    "version": "2.0.1",
    "description": "Get up and running with the google maps API quickly",
    "main": "index.js",
    "directories": {
        "test": "test"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": [
            "ie/6..latest",
            "chrome/22..latest",
            "firefox/16..latest",
            "safari/latest",
            "opera/11.0..latest",
            "iphone/6",
            "ipad/6",
            "android-browser/latest"
        ]
    },
    "scripts": {
        "test": "tape test/index.js -b"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/Jam3/google-maps-api.git"
    },
    "keywords": [
        "google",
        "maps",
        "api",
        "frontend",
        "browser"
    ],
    "author": "Mikko Haapoja <me@mikkoh.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/Jam3/google-maps-api/issues"
    },
    "homepage": "https://github.com/Jam3/google-maps-api",
    "dependencies": {
        "latlng": "^1.0.0",
        "promise": "^6.0.1",
        "scriptjs": "^2.5.7"
    },
    "devDependencies": {
        "brfs": "^1.2.0",
        "prova": "^1.14.3",
        "tape": "^3.0.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
