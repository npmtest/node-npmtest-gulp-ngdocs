# npmtest-gulp-ngdocs

#### basic test coverage for  gulp-ngdocs (v0.3.0)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-ngdocs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-ngdocs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-ngdocs.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-ngdocs)

#### gulp plugin for angularjs documentation

[![NPM](https://nodei.co/npm/gulp-ngdocs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-ngdocs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-ngdocs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-ngdocs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-ngdocs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-ngdocs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-ngdocs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-ngdocs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-ngdocs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-ngdocs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-ngdocs",
    "version": "0.3.0",
    "author": "nikhilmodak",
    "description": "gulp plugin for angularjs documentation",
    "main": "index",
    "repository": {
        "type": "git",
        "url": "https://github.com/nikhilmodak/gulp-ngdocs.git"
    },
    "keywords": [
        "gulpplugin",
        "angular",
        "gulp",
        "ngdocs",
        "documention"
    ],
    "license": "MIT",
    "readmeFilename": "README.md",
    "dependencies": {
        "angular": "~1.3.1",
        "angular-animate": "~1.3.1",
        "canonical-path": "0.0.2",
        "extend": "1.3.0",
        "gulp-util": "3.0.0",
        "lodash": "2.4.1",
        "marked": "0.3.2",
        "merge-stream": "0.1.5",
        "path": "0.4.9",
        "string_decoder": "0.10.31",
        "through2": "0.6.1",
        "vinyl-fs": "0.3.7"
    },
    "devDependencies": {
        "del": "^1.1.1",
        "gulp": "^3.8.10",
        "jasmine-node": "^1.14.5"
    },
    "scripts": {
        "test": "jasmine-node --color spec"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
