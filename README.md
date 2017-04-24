# npmdoc-express-generator

#### api documentation for  express-generator (v4.15.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-express-generator.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-express-generator) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-express-generator.svg)](https://travis-ci.org/npmdoc/node-npmdoc-express-generator)

#### Express' application generator

[![NPM](https://nodei.co/npm/express-generator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-generator)

- [https://npmdoc.github.io/node-npmdoc-express-generator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-generator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-generator/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-express-generator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-express-generator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "express-generator",
    "description": "Express' application generator",
    "version": "4.15.0",
    "author": "TJ Holowaychuk <tj@vision-media.ca>",
    "contributors": [
        "Aaron Heckmann <aaron.heckmann+github@gmail.com>",
        "Ciaran Jessup <ciaranj@gmail.com>",
        "Douglas Christopher Wilson <doug@somethingdoug.com>",
        "Guillermo Rauch <rauchg@gmail.com>",
        "Jonathan Ong <me@jongleberry.com>",
        "Roman Shtylman <shtylman+expressjs@gmail.com>"
    ],
    "keywords": [
        "express",
        "framework",
        "sinatra",
        "web",
        "rest",
        "restful",
        "router",
        "app",
        "api"
    ],
    "repository": "expressjs/generator",
    "license": "MIT",
    "dependencies": {
        "commander": "2.9.0",
        "ejs": "2.5.6",
        "mkdirp": "0.5.1",
        "sorted-object": "2.0.1"
    },
    "main": "bin/express-cli.js",
    "preferGlobal": true,
    "bin": {
        "express": "./bin/express-cli.js"
    },
    "devDependencies": {
        "eslint": "3.18.0",
        "eslint-config-standard": "7.1.0",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "mocha": "2.5.3",
        "rimraf": "2.5.4",
        "supertest": "1.2.0",
        "validate-npm-package-name": "2.2.2"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "files": [
        "LICENSE",
        "bin/",
        "templates/"
    ],
    "scripts": {
        "lint": "eslint .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-ci": "mocha --reporter spec --check-leaks test/"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
