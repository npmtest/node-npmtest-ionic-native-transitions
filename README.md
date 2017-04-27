# npmtest-ionic-native-transitions

#### basic test coverage for  [ionic-native-transitions (v1.0.3)](https://github.com/shprink/ionic-native-transitions)  [![npm package](https://img.shields.io/npm/v/npmtest-ionic-native-transitions.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ionic-native-transitions) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ionic-native-transitions.svg)](https://travis-ci.org/npmtest/node-npmtest-ionic-native-transitions)

#### Native transitions for Ionic applications

[![NPM](https://nodei.co/npm/ionic-native-transitions.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ionic-native-transitions)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ionic-native-transitions/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ionic-native-transitions/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ionic-native-transitions/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ionic-native-transitions/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/test-report.html](https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ionic-native-transitions/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ionic-native-transitions/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ionic-native-transitions/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ionic-native-transitions/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ionic-native-transitions/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "shprink"
    },
    "bugs": {
        "url": "https://github.com/shprink/ionic-native-transitions/issues"
    },
    "dependencies": {},
    "description": "Native transitions for Ionic applications",
    "devDependencies": {
        "angular-ui-router": "^0.2.15",
        "babel-core": "^5.6.15",
        "babel-loader": "^5.2.2",
        "cordova": "~5.3.0",
        "css-loader": "^0.19.0",
        "exports-loader": "^0.6.2",
        "expose-loader": "^0.6.0",
        "file-loader": "^0.8.4",
        "html-webpack-plugin": "^1.6.1",
        "ionic-angular": "^1.3.1",
        "json-loader": "^0.5.2",
        "ng-annotate-loader": "~0.0.6",
        "path": "^0.4.9",
        "style-loader": "^0.12.4",
        "util": "^0.10.3",
        "webpack": "~1.10.0",
        "webpack-dev-server": "~1.10.0"
    },
    "directories": {},
    "dist": {
        "shasum": "adcd8f54ca2010da090da575514444cf821fd0b9",
        "tarball": "https://registry.npmjs.org/ionic-native-transitions/-/ionic-native-transitions-1.0.3.tgz"
    },
    "gitHead": "cc10ca2605b16d433e6c28ee53af46a80c43c18c",
    "homepage": "https://github.com/shprink/ionic-native-transitions",
    "keywords": [
        "ionic",
        "cordova",
        "telerik",
        "angular",
        "angularjs",
        "native",
        "transition",
        "transitions"
    ],
    "license": "MIT",
    "main": "dist/ionic-native-transitions.js",
    "maintainers": [
        {
            "name": "kenmickles"
        },
        {
            "name": "shprink"
        }
    ],
    "name": "ionic-native-transitions",
    "optionalDependencies": {},
    "pearDependencies": {
        "restangular": "^1.4.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/shprink/ionic-native-transitions.git"
    },
    "scripts": {
        "android": "npm run dumpdev && npm run dumpTestDev && cordova run android",
        "build": "npm run dumpdev && npm run dumpprod",
        "dumpTestDev": "webpack --progress --colors -d",
        "dumpTestProd": "webpack --progress --colors -p",
        "dumpdev": "webpack --progress --colors --config webpack.config.dist.js -d",
        "dumpprod": "webpack --progress --colors --config webpack.config.dist.min.js -p",
        "installCordova": "npm run platformAddAll && npm run pluginAddAll",
        "ios": "npm run dumpdev && npm run dumpTestDev && cordova run ios --device",
        "iosEmulator": "npm run dumpdev && npm run dumpTestDev && cordova run ios",
        "platformAddAll": "npm run platformAddAndroid && npm run platformAddIOS",
        "platformAddAndroid": "cordova platform add android@5.x",
        "platformAddIOS": "cordova platform add ios",
        "pluginAddAll": "cordova plugin add cordova-plugin-crosswalk-webview@1.6.0 https://github.com/Telerik-Verified-Plugins/NativePageTransitions#0.6.5",
        "runAllDevice": "npm run dumpdev && npm run dumpTestDev && cordova run android && cordova run ios --device",
        "start": "webpack-dev-server --port 8080 --json --progress",
        "watch": "webpack --watch --progress --colors --config webpack.config.dist.js -d"
    },
    "version": "1.0.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
