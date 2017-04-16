# api documentation for  [express-generator (v4.15.0)](https://github.com/expressjs/generator#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-express-generator.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-express-generator) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-express-generator.svg)](https://travis-ci.org/npmdoc/node-npmdoc-express-generator)
#### Express' application generator

[![NPM](https://nodei.co/npm/express-generator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-generator)

- [https://npmdoc.github.io/node-npmdoc-express-generator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-generator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-generator/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-express-generator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-express-generator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk"
    },
    "bin": {
        "express": "./bin/express-cli.js"
    },
    "bugs": {
        "url": "https://github.com/expressjs/generator/issues"
    },
    "contributors": [
        {
            "name": "Aaron Heckmann"
        },
        {
            "name": "Ciaran Jessup"
        },
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Guillermo Rauch"
        },
        {
            "name": "Jonathan Ong"
        },
        {
            "name": "Roman Shtylman"
        }
    ],
    "dependencies": {
        "commander": "2.9.0",
        "ejs": "2.5.6",
        "mkdirp": "0.5.1",
        "sorted-object": "2.0.1"
    },
    "description": "Express' application generator",
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
    "directories": {},
    "dist": {
        "shasum": "81ba5ca8db9ceeaee281a08f5ad5c3f472430006",
        "tarball": "https://registry.npmjs.org/express-generator/-/express-generator-4.15.0.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "files": [
        "LICENSE",
        "bin/",
        "templates/"
    ],
    "gitHead": "298832e6daaba3b1759e83f4b9969a80a8ca7a0b",
    "homepage": "https://github.com/expressjs/generator#readme",
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
    "license": "MIT",
    "main": "bin/express-cli.js",
    "maintainers": [
        {
            "name": "dougwilson"
        }
    ],
    "name": "express-generator",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/generator.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-ci": "mocha --reporter spec --check-leaks test/"
    },
    "version": "4.15.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module express-generator](#apidoc.module.express-generator)



# <a name="apidoc.module.express-generator"></a>[module express-generator](#apidoc.module.express-generator)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
