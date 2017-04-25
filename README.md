# npmdoc-fetch-mock

#### basic api documentation for  [fetch-mock (v5.10.0)](http://www.wheresrhys.co.uk/fetch-mock)  [![npm package](https://img.shields.io/npm/v/npmdoc-fetch-mock.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-fetch-mock) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-fetch-mock.svg)](https://travis-ci.org/npmdoc/node-npmdoc-fetch-mock)

#### Mock http requests made using fetch (or isomorphic-fetch)

[![NPM](https://nodei.co/npm/fetch-mock.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fetch-mock)

- [https://npmdoc.github.io/node-npmdoc-fetch-mock/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fetch-mock/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fetch-mock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fetch-mock/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-fetch-mock/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-fetch-mock/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rhys Evans"
    },
    "browser": "es5/client.js",
    "bugs": {
        "url": "https://github.com/wheresrhys/fetch-mock/issues"
    },
    "dependencies": {
        "glob-to-regexp": "^0.3.0",
        "node-fetch": "^1.3.3",
        "path-to-regexp": "^1.7.0"
    },
    "description": "Mock http requests made using fetch (or isomorphic-fetch)",
    "devDependencies": {
        "babel": "^6.0.15",
        "babel-cli": "^6.1.2",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-preset-es2015": "^6.1.2",
        "babelify": "^7.3.0",
        "bluebird": "^3.4.6",
        "browserify": "^13.1.0",
        "chai": "^2.3.0",
        "eslint": "^1.10.3",
        "karma": "^1.3.0",
        "karma-browserify": "^5.1.0",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-firefox-launcher": "^1.0.0",
        "karma-mocha": "^1.2.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "mocha": "^2.2.4",
        "mockery": "^1.4.0",
        "sinon": "^1.17.0",
        "watchify": "^3.7.0",
        "whatwg-fetch": "^0.10.1"
    },
    "directories": {},
    "dist": {
        "shasum": "52e29c72800640e48410602fe076ac3615e590ad",
        "tarball": "https://registry.npmjs.org/fetch-mock/-/fetch-mock-5.10.0.tgz"
    },
    "gitHead": "11a9bf7d8b05cc3d670a82c06d7d2f36387f88c3",
    "homepage": "http://www.wheresrhys.co.uk/fetch-mock",
    "keywords": [
        "fetch",
        "http",
        "mock",
        "testing",
        "spy",
        "ajax",
        "xhr"
    ],
    "license": "MIT",
    "main": "src/server.js",
    "maintainers": [
        {
            "name": "jackfranklin"
        },
        {
            "name": "pimterry"
        },
        {
            "name": "wheresrhys"
        }
    ],
    "name": "fetch-mock",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wheresrhys/fetch-mock.git"
    },
    "scripts": {
        "browserify": "browserify -s fetchMock es5/client.js > es5/client-browserified.js",
        "prepublish": "babel src --out-dir es5 --plugins transform-object-assign --presets es2015 && npm run browserify",
        "test": "make test"
    },
    "version": "5.10.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
