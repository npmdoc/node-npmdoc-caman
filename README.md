# npmdoc-caman

#### api documentation for  [caman (v4.1.2)](http://camanjs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-caman.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-caman) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-caman.svg)](https://travis-ci.org/npmdoc/node-npmdoc-caman)

#### Javascript (Ca)nvas (Man)ipulation for NodeJS and the browser

[![NPM](https://nodei.co/npm/caman.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/caman)

- [https://npmdoc.github.io/node-npmdoc-caman/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-caman/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-caman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-caman/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-caman/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-caman/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "caman",
    "version": "4.1.2",
    "description": "Javascript (Ca)nvas (Man)ipulation for NodeJS and the browser",
    "keywords": [
        "canvas",
        "image",
        "manipulate",
        "filter",
        "image manipulation",
        "editing"
    ],
    "homepage": "http://camanjs.com",
    "author": {
        "name": "Ryan LeFevre",
        "url": "http://meltingice.net"
    },
    "engines": {
        "node": ">= 0.6.18"
    },
    "contributors": [
        {
            "name": "Rick Waldron",
            "url": "http://github.com/rwldrn"
        },
        {
            "name": "Cezar Sa Espinola",
            "url": "http://github.com/cezarsa"
        },
        {
            "name": "Jarques Pretorius",
            "url": "http://twitter.com/jarques"
        },
        {
            "name": "Hosselaer",
            "url": "https://github.com/Hosselaer"
        },
        {
            "name": "Mario Klingemann",
            "url": "http://www.quasimondo.com"
        }
    ],
    "main": "./dist/caman.full.js",
    "repository": {
        "type": "git",
        "url": "http://github.com/meltingice/CamanJS.git"
    },
    "dependencies": {
        "canvas": "*",
        "fibers": "*"
    },
    "devDependencies": {
        "coffee-script": ">= 1.6.1",
        "docco": "0.6.2",
        "codo": "*",
        "jsmin": "*",
        "packer": "*",
        "mocha": "*",
        "chai": "*",
        "servedir": "*",
        "cli": "*",
        "cli-table": "*",
        "karma": "*"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha --compilers coffee:coffee-script --reporter spec --globals Caman ./test/unit/*.coffee && ./node_modules/.bin/karma start --single-run",
        "examples": "./node_modules/servedir/bin/servedir",
        "docs": "codo",
        "docs-server": "codo --server"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
