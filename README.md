# npmdoc-autodoc

#### api documentation for  [autodoc (v0.6.4)](https://github.com/dtao/autodoc#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-autodoc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-autodoc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-autodoc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-autodoc)

#### Doc generation on steroids

[![NPM](https://nodei.co/npm/autodoc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/autodoc)

- [https://npmdoc.github.io/node-npmdoc-autodoc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-autodoc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-autodoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-autodoc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-autodoc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-autodoc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dan Tao"
    },
    "bin": {
        "autodoc": "bin/autodoc"
    },
    "bugs": {
        "url": "https://github.com/dtao/autodoc/issues"
    },
    "dependencies": {
        "benchmark": "1.0.0",
        "bootscrap": "0.1.0",
        "codemirror": "3.20.0",
        "codemirror-highlight": "1.1.1",
        "coffee-script": "^1.7.1",
        "commander": "2.0.0",
        "doctrine": "git://github.com/dtao/doctrine.git#line-numbers-option",
        "esprima": "1.0.4",
        "jasmine-node": "1.12.0",
        "lazy.js": "git://github.com/dtao/lazy.js.git",
        "less": "1.6.0",
        "marked": "0.3.2",
        "mustache": "0.7.2",
        "resolve": "0.6.1",
        "spiderman": "0.1.5",
        "string-table": "0.1.5"
    },
    "description": "Doc generation on steroids",
    "devDependencies": {
        "mocha": "1.14.0",
        "should": ">= 2.0.2",
        "sinon": ">= 1.7.3",
        "underscore": ">= 1.5.2"
    },
    "directories": {},
    "dist": {
        "shasum": "452df6f75754ea6c26ce826966bc685354d25b36",
        "tarball": "https://registry.npmjs.org/autodoc/-/autodoc-0.6.4.tgz"
    },
    "gitHead": "a0a2bc2d0b76d7358c13c2e151a5b764fc518635",
    "homepage": "https://github.com/dtao/autodoc#readme",
    "license": "MIT",
    "main": "autodoc-node.js",
    "maintainers": [
        {
            "name": "dtao"
        }
    ],
    "name": "autodoc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dtao/autodoc.git"
    },
    "scripts": {
        "test": "node bin/autodoc -t autodoc.js && node bin/autodoc -t example/redundant.js && mocha --compilers coffee:coffee-script/register"
    },
    "version": "0.6.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
