# test coverage for  [ember-component-css (v0.3.2)](https://github.com/ebryn/ember-component-css#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-component-css.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-component-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-component-css.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-component-css)
#### An Ember CLI addon which allows you to specify styles for individual components

[![NPM](https://nodei.co/npm/ember-component-css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-component-css)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-component-css/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-component-css/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-component-css/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-component-css/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-component-css/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-component-css/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-component-css/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-component-css/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-component-css/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-component-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-component-css/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-component-css/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-component-css/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-component-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-component-css/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-component-css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-component-css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-component-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-component-css/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-component-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-component-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Erik Bryn"
    },
    "bugs": {
        "url": "https://github.com/ebryn/ember-component-css/issues"
    },
    "dependencies": {
        "broccoli-concat": "^3.0.5",
        "broccoli-funnel": "^1.0.9",
        "broccoli-merge-trees": "^2.0.0",
        "broccoli-persistent-filter": "1.2.13",
        "broccoli-plugin": "^1.2.1",
        "broccoli-style-manifest": "^1.2.2",
        "ember-cli-babel": "^5.1.7",
        "ember-getowner-polyfill": "^1.1.1",
        "fs-tree-diff": "^0.5.6",
        "md5": "^2.1.0",
        "postcss": "^5.2.10",
        "postcss-less": "^0.15.0",
        "postcss-scss": "^0.4.0",
        "postcss-selector-namespace": "^1.3.0",
        "rsvp": "^3.2.1",
        "walk-sync": "^0.3.1"
    },
    "description": "An Ember CLI addon which allows you to specify styles for individual components",
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.5",
        "ember-cli": "2.12.0",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-eslint": "^3.0.0",
        "ember-cli-htmlbars": "^1.1.1",
        "ember-cli-htmlbars-inline-precompile": "^0.3.6",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-qunit": "^3.1.0",
        "ember-cli-shims": "^1.0.2",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-styles-preprocessor": "^0.0.7",
        "ember-cli-uglify": "^1.2.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.6.0",
        "ember-resolver": "^2.0.3",
        "ember-source": "~2.12.0",
        "loader.js": "^4.2.3",
        "no-style-files-yet": "file:./tests/dummy/lib/no-style-files-yet",
        "second-test-addon": "file:./tests/dummy/lib/second-test-addon",
        "test-addon": "file:./tests/dummy/lib/test-addon"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "50d3c17e0b057a3cb5bf728540613f0038bcf653",
        "tarball": "https://registry.npmjs.org/ember-component-css/-/ember-component-css-0.3.2.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "before": [
            "ember-cli-styles-preprocessor",
            "ember-cli-less",
            "ember-cli-sass",
            "ember-cli-stylus",
            "ember-cli-postcss"
        ]
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "61583c9876af98b84f680eaef02dfbe9aaf21a0f",
    "homepage": "https://github.com/ebryn/ember-component-css#readme",
    "keywords": [
        "ember-addon"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "ebryn"
        },
        {
            "name": "webark"
        }
    ],
    "name": "ember-component-css",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ebryn/ember-component-css.git"
    },
    "scripts": {
        "build": "ember build",
        "prepublish": "./bin/install-test-addons.sh",
        "start": "ember server",
        "test": "ember try:each"
    },
    "version": "0.3.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
