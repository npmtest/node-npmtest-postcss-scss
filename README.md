# npmtest-postcss-scss

#### basic test coverage for  [postcss-scss (v0.4.1)](https://github.com/postcss/postcss-scss#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-postcss-scss.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-postcss-scss) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-postcss-scss.svg)](https://travis-ci.org/npmtest/node-npmtest-postcss-scss)

#### SCSS parser for PostCSS

[![NPM](https://nodei.co/npm/postcss-scss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/postcss-scss)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-postcss-scss/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-scss/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-scss/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-postcss-scss/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-scss/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-postcss-scss/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-postcss-scss/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-postcss-scss/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-postcss-scss/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-scss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-postcss-scss/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-postcss-scss/build/test-report.html](https://npmtest.github.io/node-npmtest-postcss-scss/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-postcss-scss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-postcss-scss/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-postcss-scss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-postcss-scss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-postcss-scss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-postcss-scss/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-postcss-scss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-postcss-scss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrey Sitnik"
    },
    "bugs": {
        "url": "https://github.com/postcss/postcss-scss/issues"
    },
    "dependencies": {
        "postcss": "^5.2.13"
    },
    "description": "SCSS parser for PostCSS",
    "devDependencies": {
        "ava": "^0.18.1",
        "babel-core": "^6.23.1",
        "babel-eslint": "^7.1.1",
        "babel-plugin-add-module-exports": "0.2.1",
        "babel-plugin-precompile-charcodes": "1.0.0",
        "babel-preset-es2015": "^6.22.0",
        "del": "2.2.2",
        "eslint": "^3.15.0",
        "eslint-config-postcss": "2.0.2",
        "gulp": "3.9.1",
        "gulp-ava": "^0.16.0",
        "gulp-babel": "6.1.2",
        "gulp-changed": "1.3.2",
        "gulp-eslint": "3.0.1",
        "gulp-json-editor": "2.2.1",
        "gulp-sourcemaps": "^2.4.1",
        "lint-staged": "^3.3.0",
        "postcss-parser-tests": "^5.0.11",
        "pre-commit": "^1.2.2",
        "run-sequence": "1.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "ad771b81f0f72f5f4845d08aa60f93557653d54c",
        "tarball": "https://registry.npmjs.org/postcss-scss/-/postcss-scss-0.4.1.tgz"
    },
    "homepage": "https://github.com/postcss/postcss-scss#readme",
    "keywords": [
        "css",
        "postcss",
        "postcss-syntax",
        "parser",
        "scss",
        "sass"
    ],
    "license": "MIT",
    "lint-staged": {
        "test/*.js": "eslint",
        "lib/*.es6": "eslint"
    },
    "main": "lib/scss-syntax",
    "maintainers": [
        {
            "name": "ai"
        }
    ],
    "name": "postcss-scss",
    "optionalDependencies": {},
    "pre-commit": [
        "lint-staged"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/postcss/postcss-scss.git"
    },
    "scripts": {
        "lint-staged": "lint-staged",
        "test": "gulp"
    },
    "version": "0.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
