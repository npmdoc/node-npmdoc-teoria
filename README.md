# npmdoc-teoria

#### basic api documentation for  [teoria (v2.2.2)](http://saebekassebil.github.com/teoria)  [![npm package](https://img.shields.io/npm/v/npmdoc-teoria.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-teoria) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-teoria.svg)](https://travis-ci.org/npmdoc/node-npmdoc-teoria)

#### Music theory for JavaScript

[![NPM](https://nodei.co/npm/teoria.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/teoria)

- [https://npmdoc.github.io/node-npmdoc-teoria/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-teoria/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-teoria/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-teoria/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-teoria/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-teoria/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jakob Miland",
        "url": "https://github.com/saebekassebil"
    },
    "bugs": {
        "url": "https://github.com/saebekassebil/teoria/issues"
    },
    "dependencies": {
        "daccord": "^1.0.1",
        "helmholtz": "^2.0.1",
        "interval-coords": "^1.1.1",
        "pitch-fq": "^1.0.0",
        "scientific-notation": "^1.0.2"
    },
    "description": "Music theory for JavaScript",
    "devDependencies": {
        "jshint": ">=0.9.0",
        "vows": ">= 0.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2f073ba64e9dd72d2c2f87634499d5ef97d2ee59",
        "tarball": "https://registry.npmjs.org/teoria/-/teoria-2.2.2.tgz"
    },
    "gitHead": "7bbde192d5bc09b36f2b1a36d239e1a404c85f7b",
    "homepage": "http://saebekassebil.github.com/teoria",
    "keywords": [
        "music",
        "theory",
        "jazz",
        "classical",
        "chord"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "saebekassebil"
        }
    ],
    "name": "teoria",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/saebekassebil/teoria.git"
    },
    "scripts": {
        "build": "npm run lint && npm test && npm run bundle",
        "bundle": "browserify index.js --standalone teoria > teoria.js",
        "lint": "jshint index.js lib/",
        "test": "vows --dot-matric test/*"
    },
    "version": "2.2.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
