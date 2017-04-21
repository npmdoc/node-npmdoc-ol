# npmdoc-ol

#### api documentation for  ol (v4.1.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-ol.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ol) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ol.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ol)

#### OpenLayers as ES2015 modules

[![NPM](https://nodei.co/npm/ol.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ol)

- [https://npmdoc.github.io/node-npmdoc-ol/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ol/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ol/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ol/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ol/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ol/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ol",
    "version": "4.1.0",
    "description": "OpenLayers as ES2015 modules",
    "main": "index.js",
    "module": "index.js",
    "license": "BSD-2-Clause",
    "dependencies": {
        "pbf": "3.0.5",
        "pixelworks": "1.1.0",
        "rbush": "2.0.1",
        "vector-tile": "1.3.0"
    },
    "browserify": {
        "transform": [
            [
                "babelify",
                {
                    "plugins": [
                        "transform-es2015-modules-commonjs"
                    ]
                }
            ]
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
