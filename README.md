# npmdoc-lodash-webpack-plugin

#### basic api documentation for  [lodash-webpack-plugin (v0.11.2)](https://github.com/lodash/lodash-webpack-plugin#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-lodash-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-lodash-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-lodash-webpack-plugin.svg)](https://travis-ci.org/npmdoc/node-npmdoc-lodash-webpack-plugin)

#### Smaller modular Lodash builds.

[![NPM](https://nodei.co/npm/lodash-webpack-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lodash-webpack-plugin)

- [https://npmdoc.github.io/node-npmdoc-lodash-webpack-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lodash-webpack-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lodash-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lodash-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-lodash-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-lodash-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "John-David Dalton",
        "url": "http://allyoucanleet.com/"
    },
    "bugs": {
        "url": "https://github.com/lodash/lodash-webpack-plugin/issues"
    },
    "contributors": [
        {
            "name": "John-David Dalton",
            "url": "http://allyoucanleet.com/"
        },
        {
            "name": "Mathias Bynens",
            "url": "https://mathiasbynens.be/"
        }
    ],
    "dependencies": {
        "lodash": "^4.17.4"
    },
    "description": "Smaller modular Lodash builds.",
    "devDependencies": {
        "babel-cli": "^6.22.2",
        "babel-core": "^6.23.1",
        "babel-loader": "^6.3.2",
        "babel-plugin-add-module-exports": "~0.2.1",
        "babel-plugin-lodash": "^3.2.11",
        "babel-preset-env": "^1.1.8",
        "chai": "^3.5.0",
        "glob": "^7.1.1",
        "gzip-size": "^3.0.0",
        "memory-fs": "^0.4.1",
        "mocha": "^3.2.0",
        "pify": "^2.3.0",
        "pretty-bytes": "^4.0.2",
        "webpack": "^2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fdb945b1ae94617172da172f20b60264cfbac635",
        "tarball": "https://registry.npmjs.org/lodash-webpack-plugin/-/lodash-webpack-plugin-0.11.2.tgz"
    },
    "files": [
        "lib"
    ],
    "homepage": "https://github.com/lodash/lodash-webpack-plugin#readme",
    "keywords": [
        "lodash",
        "modules",
        "webpack-plugin"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "jdalton"
        },
        {
            "name": "mathias"
        }
    ],
    "name": "lodash-webpack-plugin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lodash/lodash-webpack-plugin.git"
    },
    "scripts": {
        "build": "babel src --out-dir lib || true",
        "prepublish": "npm run build",
        "test": "mocha --check-leaks --slow 1e3 --compilers js:babel-core/register"
    },
    "version": "0.11.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
