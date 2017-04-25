# npmtest-grunt-styleguide

#### basic test coverage for  [grunt-styleguide (v0.2.17)](https://github.com/indieisaconcept/grunt-styleguide)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-styleguide.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-styleguide) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-styleguide.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-styleguide)

#### Universal CSS styleguide generator for grunt. Easily integrate Styledocco or KSS styleguide generation into your development workflow.

[![NPM](https://nodei.co/npm/grunt-styleguide.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-styleguide)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-styleguide/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-styleguide/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-styleguide/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-styleguide/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-styleguide/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-grunt-styleguide/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-grunt-styleguide/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-styleguide/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-styleguide/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-styleguide/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-styleguide/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-styleguide/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-styleguide/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-styleguide/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-styleguide/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-styleguide/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-styleguide/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-styleguide/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-styleguide/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-styleguide/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-styleguide/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-styleguide/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-styleguide/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-styleguide",
    "description": "Universal CSS styleguide generator for grunt. Easily integrate Styledocco or KSS styleguide generation into your development workflow.",
    "version": "0.2.17",
    "homepage": "https://github.com/indieisaconcept/grunt-styleguide",
    "author": {
        "name": "Jonathan Barnett",
        "url": "http://twitter.com/indieisaconcept"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/indieisaconcept/grunt-styleguide.git"
    },
    "bugs": {
        "url": "https://github.com/indieisaconcept/grunt-styleguide/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/indieisaconcept/grunt-styleguide/blob/master/LICENSE-MIT"
        }
    ],
    "main": "Gruntfile.js",
    "engines": {
        "node": ">= 0.8.0"
    },
    "scripts": {
        "test": "grunt test"
    },
    "devDependencies": {
        "grunt": "~0.4.5",
        "grunt-contrib-clean": "~0.6.0",
        "grunt-contrib-jshint": "~0.10.0",
        "grunt-contrib-nodeunit": "~0.4.1"
    },
    "peerDependencies": {
        "grunt": "~0.4.0"
    },
    "dependencies": {
        "wrench": "~1.5.8",
        "styledocco": "~0.6.6",
        "less": "1.x.x",
        "kss": "~1.0.1",
        "stylus": "~0.49.1"
    },
    "keywords": [
        "gruntplugin",
        "scss",
        "sass",
        "css",
        "less",
        "stylus",
        "preprocessor",
        "styleguide"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
