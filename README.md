# npmdoc-group-css-media-queries

#### api documentation for  group-css-media-queries (v1.4.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-group-css-media-queries.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-group-css-media-queries) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-group-css-media-queries.svg)](https://travis-ci.org/npmdoc/node-npmdoc-group-css-media-queries)

#### CSS postprocessing: group media queries. Useful for postprocessing preprocessed CSS files :)

[![NPM](https://nodei.co/npm/group-css-media-queries.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/group-css-media-queries)

- [https://npmdoc.github.io/node-npmdoc-group-css-media-queries/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-group-css-media-queries/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-group-css-media-queries/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-group-css-media-queries/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-group-css-media-queries/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-group-css-media-queries/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "group-css-media-queries",
    "description": "CSS postprocessing: group media queries. Useful for postprocessing preprocessed CSS files :)",
    "keywords": [
        "css",
        "group",
        "media",
        "queries",
        "postprocessing",
        "postprocessor"
    ],
    "license": "MIT",
    "author": {
        "name": "Ivan Kravchenko"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/Se7enSky/group-css-media-queries.git"
    },
    "version": "1.4.1",
    "main": "index",
    "bin": {
        "group-css-media-queries": "./bin/group-css-media-queries"
    },
    "dependencies": {
        "css-parse": "^2.0.0",
        "css-stringify": "^2.0.0"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "devDependencies": {
        "chai": "^1.10.0",
        "coffee-script": "*",
        "mocha": "^2.0.1"
    },
    "scripts": {
        "prepublish": "./node_modules/.bin/coffee -c index.coffee",
        "test": "./node_modules/.bin/mocha --compilers coffee:coffee-script/register"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
