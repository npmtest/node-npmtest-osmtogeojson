# npmtest-osmtogeojson

#### basic test coverage for  osmtogeojson (v3.0.0-beta.0)  [![npm package](https://img.shields.io/npm/v/npmtest-osmtogeojson.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-osmtogeojson) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-osmtogeojson.svg)](https://travis-ci.org/npmtest/node-npmtest-osmtogeojson)

#### convert OSM to geojson

[![NPM](https://nodei.co/npm/osmtogeojson.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/osmtogeojson)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-osmtogeojson/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-osmtogeojson/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-osmtogeojson/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-osmtogeojson/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-osmtogeojson/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-osmtogeojson/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-osmtogeojson/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-osmtogeojson/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-osmtogeojson/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-osmtogeojson/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-osmtogeojson/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-osmtogeojson/build/test-report.html](https://npmtest.github.io/node-npmtest-osmtogeojson/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-osmtogeojson/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-osmtogeojson/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-osmtogeojson/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-osmtogeojson/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-osmtogeojson/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-osmtogeojson/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-osmtogeojson/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-osmtogeojson/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "osmtogeojson",
    "version": "3.0.0-beta.0",
    "description": "convert OSM to geojson",
    "main": "index.js",
    "scripts": {
        "pretest": "npm ls --depth=Infinity > /dev/null",
        "test": "npm run test-lib && npm run test-cli",
        "test-lib": "mocha -R spec",
        "test-cli": "node test-cli/cli.test.js | faucet"
    },
    "bin": {
        "osmtogeojson": "osmtogeojson"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/tyrasd/osmtogeojson.git"
    },
    "keywords": [
        "openstreetmap",
        "geojson"
    ],
    "author": "Martin Raifer",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/tyrasd/osmtogeojson/issues"
    },
    "dependencies": {
        "JSONStream": "0.8.0",
        "concat-stream": "~1.0.1",
        "geojson-numeric": "0.2.0",
        "geojson-rewind": "0.2.0",
        "htmlparser2": "3.5.1",
        "optimist": "~0.3.5",
        "osm-polygon-features": "^0.9.1",
        "tiny-osmpbf": "^0.1.0",
        "xmldom": "~0.1.16"
    },
    "devDependencies": {
        "expect.js": "~0.2.0",
        "mocha": "~1.12.0",
        "tape": "~2.10.2",
        "faucet": "~0.0.1"
    },
    "engines": {
        "node": ">=0.5"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
