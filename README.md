# npmtest-cordova-plugin-admob-simple

#### basic test coverage for  cordova-plugin-admob-simple (v3.2.1)  [![npm package](https://img.shields.io/npm/v/npmtest-cordova-plugin-admob-simple.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cordova-plugin-admob-simple) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cordova-plugin-admob-simple.svg)](https://travis-ci.org/npmtest/node-npmtest-cordova-plugin-admob-simple)

#### The FASTEST and EASIEST TO USE Cordova Admob plugin for Android, iOS and Windows phone. We do not send your apps details to our servers. Pure OpenSource Admob code. Allows preloading and automatic loading of interstitials and banners plus more. Works with Cordova, Phonegap, Intel XDK/Crosswalk, Ionic, Meteor and more.

[![NPM](https://nodei.co/npm/cordova-plugin-admob-simple.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cordova-plugin-admob-simple)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cordova-plugin-admob-simple/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cordova-plugin-admob-simple/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/test-report.html](https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cordova-plugin-admob-simple/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cordova-plugin-admob-simple/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cordova-plugin-admob-simple/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cordova-plugin-admob-simple/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cordova-plugin-admob-simple/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cordova-plugin-admob-simple",
    "version": "3.2.1",
    "description": "The FASTEST and EASIEST TO USE Cordova Admob plugin for Android, iOS and Windows phone. We do not send your apps details to our servers. Pure OpenSource Admob code. Allows preloading and automatic loading of interstitials and banners plus more. Works with Cordova, Phonegap, Intel XDK/Crosswalk, Ionic, Meteor and more.",
    "cordova": {
        "id": "cordova-plugin-admob-simple",
        "platforms": [
            "android",
            "ios",
            "wp8",
            "windows"
        ]
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/sunnycupertino/cordova-plugin-admob-simple.git"
    },
    "bugs": {
        "url": "https://github.com/sunnycupertino/cordova-plugin-admob-simple/issues"
    },
    "keywords": [
        "cordova",
        "admob",
        "plugin",
        "phonegap",
        "intel-xdk",
        "intel",
        "xdk",
        "crosswalk",
        "ionic",
        "meteor",
        "ad",
        "ecosystem:cordova",
        "cordova-android",
        "cordova-ios",
        "cordova-wp8",
        "google",
        "ads",
        "eclipse",
        "android-studio",
        "simple",
        "android",
        "ios",
        "windows",
        "phonegap",
        "monetization",
        "monetisation",
        "money",
        "banner",
        "interstitial",
        "advertisement",
        "advertising",
        "earn",
        "cordova-admob",
        "admobpro"
    ],
    "tonicExampleFilename": "test.js",
    "author": {
        "name": "Cupertino"
    },
    "license": "MIT",
    "scripts": {
        "clean": "rimraf www",
        "build": "babel src/js --out-dir www",
        "version": "sync-package-version --cordova-plugin",
        "test": "cordova-test"
    },
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-preset-es2015": "^6.18.0",
        "cordova-android": "^6.0.0",
        "cordova-test-cli": "0.0.1",
        "npm-run-all": "^3.1.1",
        "rimraf": "^2.5.4",
        "sync-package-version": "0.0.3"
    },
    "babel": {
        "presets": [
            "es2015"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
