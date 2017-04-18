# api documentation for  [preprocessor (v1.4.0)](https://github.com/dcodeIO/Preprocessor.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-preprocessor.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-preprocessor) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-preprocessor.svg)](https://travis-ci.org/npmdoc/node-npmdoc-preprocessor)
#### Preprocessor.js: A JavaScript source file preprocessor, e.g. to build different versions of a library.

[![NPM](https://nodei.co/npm/preprocessor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/preprocessor)

- [https://npmdoc.github.io/node-npmdoc-preprocessor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-preprocessor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-preprocessor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-preprocessor/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-preprocessor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-preprocessor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Wirtz"
    },
    "bin": {
        "preprocess": "./bin/preprocess"
    },
    "bugs": {
        "url": "https://github.com/dcodeIO/Preprocessor.js/issues"
    },
    "dependencies": {
        "glob": "~3.2"
    },
    "description": "Preprocessor.js: A JavaScript source file preprocessor, e.g. to build different versions of a library.",
    "devDependencies": {
        "closurecompiler": "latest",
        "testjs": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "b9c5b4dcbf236508f8cfe9105de2fe1272aa5179",
        "tarball": "https://registry.npmjs.org/preprocessor/-/preprocessor-1.4.0.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "homepage": "https://github.com/dcodeIO/Preprocessor.js",
    "keywords": [
        "source",
        "source code",
        "JavaScript",
        "ECMAScript",
        "preprocessor",
        "pre-processor",
        "pre processor",
        "processor",
        "utility"
    ],
    "license": "Apache License, Version 2.0",
    "main": "Preprocessor.js",
    "maintainers": [
        {
            "name": "dcode"
        }
    ],
    "name": "preprocessor",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dcodeIO/Preprocessor.js.git"
    },
    "scripts": {
        "compile": "ccjs Preprocessor.js --create_source_map=Preprocessor.min.map --compilation_level=ADVANCED_OPTIMIZATIONS --externs=node > Preprocessor.min.js",
        "jsdoc": "jsdoc -c jsdoc.json",
        "make": "npm run-script compile && npm test && npm run-script jsdoc",
        "prepublish": "npm test",
        "test": "node node_modules/testjs/bin/testjs tests/suite.js"
    },
    "version": "1.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
