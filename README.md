# npmtest-nativescript-angular

#### test coverage for  [nativescript-angular (v1.5.1)](http://www.telerik.com)  [![npm package](https://img.shields.io/npm/v/npmtest-nativescript-angular.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nativescript-angular) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nativescript-angular.svg)](https://travis-ci.org/npmtest/node-npmtest-nativescript-angular)

#### An Angular 2 renderer that lets you build mobile apps with NativeScript.

[![NPM](https://nodei.co/npm/nativescript-angular.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nativescript-angular)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nativescript-angular/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nativescript-angular/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nativescript-angular/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nativescript-angular/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nativescript-angular/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nativescript-angular/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nativescript-angular/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nativescript-angular/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nativescript-angular/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nativescript-angular/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nativescript-angular/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nativescript-angular/build/test-report.html](https://npmtest.github.io/node-npmtest-nativescript-angular/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nativescript-angular/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nativescript-angular/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nativescript-angular/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nativescript-angular/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nativescript-angular/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nativescript-angular/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nativescript-angular/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nativescript-angular/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "update-app-ng-deps": "./bin/update-app-ng-deps"
    },
    "bugs": {
        "url": "http://www.telerik.com"
    },
    "contributors": [
        {
            "name": "Hristo Deshev"
        }
    ],
    "dependencies": {
        "@angular/common": "~4.0.0",
        "@angular/compiler": "~4.0.0",
        "@angular/core": "~4.0.0",
        "@angular/forms": "~4.0.0",
        "@angular/http": "~4.0.0",
        "@angular/platform-browser": "~4.0.0",
        "@angular/platform-browser-dynamic": "~4.0.0",
        "@angular/router": "~4.0.0",
        "nativescript-intl": "~0.0.8",
        "punycode": "1.3.2",
        "querystring": "0.2.0",
        "reflect-metadata": "~0.1.8",
        "rxjs": "^5.0.1",
        "url": "0.10.3"
    },
    "description": "An Angular 2 renderer that lets you build mobile apps with NativeScript.",
    "devDependencies": {
        "@angular/animations": "~4.0.0",
        "@angular/compiler-cli": "~4.0.0",
        "codelyzer": "~2.0.0",
        "tns-core-modules": ">=2.5.0 || >=2.5.0-2016",
        "tslint": "~4.0.1",
        "typescript": "~2.1.1",
        "zone.js": "^0.8.2"
    },
    "directories": {},
    "dist": {
        "shasum": "5942dbb11930461f356ef0e272cd6a91c08bcf61",
        "tarball": "https://registry.npmjs.org/nativescript-angular/-/nativescript-angular-1.5.1.tgz"
    },
    "homepage": "http://www.telerik.com",
    "license": "Apache-2.0",
    "maintainers": [
        {
            "name": "hdeshev"
        },
        {
            "name": "tns-bot"
        },
        {
            "name": "vakrilov"
        }
    ],
    "name": "nativescript-angular",
    "nativescript": {},
    "optionalDependencies": {},
    "private": false,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/NativeScript/nativescript-angular.git"
    },
    "scripts": {
        "ngc": "ngc -p tsconfig.json",
        "postinstall": "node postinstall.js",
        "tsc": "tsc -p tsconfig.json",
        "tslint": "tslint --project tsconfig.json --config tslint.json"
    },
    "version": "1.5.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
