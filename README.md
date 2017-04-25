# npmtest-svg.js

#### basic test coverage for  [svg.js (v2.6.0)](https://svgdotjs.github.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-svg.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-svg.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-svg.js.svg)](https://travis-ci.org/npmtest/node-npmtest-svg.js)

#### A lightweight library for manipulating and animating SVG.

[![NPM](https://nodei.co/npm/svg.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/svg.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-svg.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-svg.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-svg.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-svg.js/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-svg.js/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-svg.js/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-svg.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-svg.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-svg.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-svg.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-svg.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-svg.js/build/test-report.html](https://npmtest.github.io/node-npmtest-svg.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-svg.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-svg.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-svg.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-svg.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-svg.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-svg.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-svg.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-svg.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Wout Fierens"
    },
    "bugs": {
        "url": "https://github.com/svgdotjs/svg.js/issues"
    },
    "dependencies": {},
    "description": "A lightweight library for manipulating and animating SVG.",
    "devDependencies": {
        "coveralls": "^2.11.15",
        "del": "^2.2.0",
        "gulp": "^3.8.6",
        "gulp-chmod": "^2.0.0",
        "gulp-cli": "^1.2.2",
        "gulp-concat": "^2.3.3",
        "gulp-header": "^1.0.5",
        "gulp-rename": "^1.2.0",
        "gulp-size": "^2.1.0",
        "gulp-trimlines": "^1.0.0",
        "gulp-uglify": "^2.0.0",
        "gulp-wrap": "^0.13.0",
        "jasmine-core": "^2.5.2",
        "karma": "^1.3.0",
        "karma-coverage": "^1.1.1",
        "karma-firefox-launcher": "^1.0.0",
        "karma-jasmine": "^1.0.2",
        "karma-phantomjs-launcher": "^1.0.2",
        "request": "^2.78.0",
        "svgdom": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "13c01e5b2d267734d12531621cefabe49742dcb2",
        "tarball": "https://registry.npmjs.org/svg.js/-/svg.js-2.6.0.tgz"
    },
    "gitHead": "04e21b18c30d546ed6a16b279504a2b58b503541",
    "github": "https://github.com/svgdotjs/svg.js",
    "homepage": "https://svgdotjs.github.io/",
    "jam": {
        "include": [
            "dist/svg.js",
            "README.md",
            "LICENSE.txt"
        ]
    },
    "keywords": [
        "svg",
        "vector",
        "graphics",
        "animation"
    ],
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/mit-license.php"
        }
    ],
    "main": "dist/svg.js",
    "maintainers": [
        {
            "name": "dotnetcarpenter"
        },
        {
            "name": "fuzzyma"
        },
        {
            "name": "wout"
        }
    ],
    "name": "svg.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/svgdotjs/svg.js.git"
    },
    "scripts": {
        "build": "gulp",
        "build:test": "gulp unify",
        "test": "karma start .config/karma.conf.js --single-run",
        "test:quick": "karma start .config/karma.quick.js"
    },
    "typings": "./svg.js.d.ts",
    "url": "https://svgdotjs.github.io/",
    "version": "2.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
