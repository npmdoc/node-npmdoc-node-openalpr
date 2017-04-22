# npmdoc-node-openalpr

#### api documentation for  node-openalpr (v1.1.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-openalpr.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-openalpr) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-openalpr.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-openalpr)

#### Node.js OpenALPR Bindings

[![NPM](https://nodei.co/npm/node-openalpr.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-openalpr)

- [https://npmdoc.github.io/node-npmdoc-node-openalpr/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-openalpr/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-openalpr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-openalpr/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-openalpr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-openalpr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-openalpr",
    "description": "Node.js OpenALPR Bindings",
    "version": "1.1.1",
    "license": "AGPL",
    "keywords": [
        "bindings",
        "license",
        "plate",
        "recognition",
        "lpr",
        "openalpr"
    ],
    "author": {
        "name": "netPark",
        "url": "https://www.netpark.us"
    },
    "contributors": [
        {
            "name": "Kevin Lawrence"
        }
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/netPark/node-openalpr.git"
    },
    "dependencies": {
        "fs-extra": "^0.23.1",
        "nan": "^2.0.5",
        "node-pre-gyp": "https://github.com/mapbox/node-pre-gyp.git"
    },
    "main": "./src/openalpr",
    "binary": {
        "module_name": "node_openalpr",
        "module_path": "release/{platform}_{arch}/",
        "host": ""
    },
    "engines": {
        "node": ">= 4.0.0",
        "iojs": ">= 3.0.0"
    },
    "scripts": {
        "install": "node-pre-gyp install --build-from-source --fallback-to-build",
        "postinstall": "node -e \"var fs = require('fs-extra'); fs.remove ('build');\""
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
