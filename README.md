# api documentation for  [roots (v5.1.0)](http://roots.cx)  [![npm package](https://img.shields.io/npm/v/npmdoc-roots.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-roots) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-roots.svg)](https://travis-ci.org/npmdoc/node-npmdoc-roots)
#### simple, flexible, and powerful static site compiler

[![NPM](https://nodei.co/npm/roots.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/roots)

- [https://npmdoc.github.io/node-npmdoc-roots/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-roots/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-roots/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-roots/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-roots/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-roots/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeff Escalante"
    },
    "bin": {
        "roots": "bin/roots"
    },
    "bugs": {
        "url": "https://github.com/jenius/roots/issues"
    },
    "contributors": [
        {
            "name": "Sam Saccone"
        }
    ],
    "dependencies": {
        "accord": "0.26.4",
        "argparse": "1.x",
        "browser-sync": "^2.12.5",
        "charge": "0.1.x",
        "chokidar": "^1.5.0",
        "coffee-script": "1.12.1",
        "colors": "1.x",
        "configstore": "^2.0.0",
        "graceful-fs": "^4.1.9",
        "inquirer": "^2.0.0",
        "keen.io": "0.1.x",
        "lodash": "^4.12.0",
        "micromatch": "^2.3.8",
        "mkdirp": "0.5.x",
        "npm": "^4.0.3",
        "open": "0.0.5",
        "osenv": "0.1.x",
        "readdirp": "2.x",
        "rimraf": "2.x",
        "serve-static": "1.x",
        "sprout": "^1.1.0",
        "update-notifier": "^1.0.0",
        "vinyl": "2.0.1",
        "when": "3.x"
    },
    "description": "simple, flexible, and powerful static site compiler",
    "devDependencies": {
        "chai": "3.x",
        "chai-as-promised": "6.0.0",
        "chai-fs": "github:jenius/chai-fs",
        "coffeelint": "^1.15.7",
        "coveralls": "2.x",
        "glob": "^7.0.3",
        "istanbul": "^0.4.3",
        "mocha": "2.x",
        "mocha-lcov-reporter": "^1.2.0",
        "mockery": "^2.0.0",
        "roots-util": "^0.2.0",
        "sinon": "^1.17.4",
        "sinon-chai": "2.x"
    },
    "directories": {
        "lib": "lib",
        "bin": "bin"
    },
    "dist": {
        "shasum": "e3a38e385b8197188e3d3f2bc7651e23beea2301",
        "tarball": "https://registry.npmjs.org/roots/-/roots-5.1.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "24401170985e5dc62a1209e1a39436efb4f39dad",
    "homepage": "http://roots.cx",
    "keywords": [
        "roots",
        "static"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "jescalan"
        }
    ],
    "name": "roots",
    "optionalDependencies": {},
    "readmeFilename": "readme.md",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jenius/roots.git"
    },
    "scripts": {
        "coverage": "make build; istanbul cover _mocha --report html -- -R spec && open coverage/index.html && make unbuild",
        "coveralls": "make build; istanbul cover _mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | coveralls && rm -rf ./coverage; make unbuild",
        "lint": "coffeelint lib",
        "postinstall": "node ./post_install.js",
        "test": "npm run lint && mocha"
    },
    "version": "5.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
