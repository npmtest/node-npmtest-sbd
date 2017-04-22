# npmtest-sbd

#### basic test coverage for  [sbd (v1.0.12)](http://github.com/Tessmore/sbd)  [![npm package](https://img.shields.io/npm/v/npmtest-sbd.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sbd) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sbd.svg)](https://travis-ci.org/npmtest/node-npmtest-sbd)

#### Split text into sentences with Sentence Boundary Detection (SBD).

[![NPM](https://nodei.co/npm/sbd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sbd)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sbd/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sbd/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sbd/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sbd/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sbd/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sbd/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sbd/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sbd/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sbd/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sbd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sbd/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sbd/build/test-report.html](https://npmtest.github.io/node-npmtest-sbd/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sbd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sbd/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sbd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sbd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sbd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sbd/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sbd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sbd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Fabiën Tesselaar"
    },
    "browser": {
        "sanitize-html": "./lib/sanitize-html-browser.js"
    },
    "bugs": {
        "url": "https://github.com/Tessmore/sbd/issues"
    },
    "dependencies": {
        "sanitize-html": "^1.11.2"
    },
    "description": "Split text into sentences with Sentence Boundary Detection (SBD).",
    "devDependencies": {
        "mocha": "3.0.x"
    },
    "directories": {},
    "dist": {
        "shasum": "cd2288f6158ead8214434cd8209630eb1d94828d",
        "tarball": "https://registry.npmjs.org/sbd/-/sbd-1.0.12.tgz"
    },
    "gitHead": "16ab804fbf51b6a8946be64ce39621005f710b5e",
    "homepage": "http://github.com/Tessmore/sbd",
    "keywords": [
        "sentence",
        "detection",
        "boundary"
    ],
    "license": "MIT",
    "main": "lib/tokenizer.js",
    "maintainers": [
        {
            "name": "tessmore"
        }
    ],
    "name": "sbd",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Tessmore/sbd.git"
    },
    "scripts": {
        "build": "npm run build:js && npm run build:minify",
        "build:js": "browserify lib/tokenizer.js --standalone tokenizer > dist/sbd.js",
        "build:minify": "uglifyjs dist/sbd.js > dist/sbd.min.js",
        "test": "mocha -R spec"
    },
    "version": "1.0.12",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
