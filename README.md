# npmdoc-jsx-chai

#### api documentation for  [jsx-chai (v4.0.0)](https://github.com/bkonkle/jsx-chai#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-jsx-chai.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jsx-chai) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jsx-chai.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jsx-chai)

#### JSX assertions for Chai using Algolia's react-element-to-jsx-string

[![NPM](https://nodei.co/npm/jsx-chai.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsx-chai)

- [https://npmdoc.github.io/node-npmdoc-jsx-chai/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsx-chai/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsx-chai/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsx-chai/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jsx-chai/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jsx-chai/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jsx-chai",
    "version": "4.0.0",
    "description": "JSX assertions for Chai using Algolia's react-element-to-jsx-string",
    "main": "lib/jsx-chai.js",
    "scripts": {
        "test": "istanbul cover _mocha",
        "build": "babel-node $(which gulp) build"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bkonkle/jsx-chai.git"
    },
    "keywords": [
        "chai",
        "testing",
        "assertions",
        "jsx",
        "react"
    ],
    "author": "Brandon Konkle <brandon@konkle.us>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/bkonkle/jsx-chai/issues"
    },
    "homepage": "https://github.com/bkonkle/jsx-chai#readme",
    "peerDependencies": {
        "chai": "^3.4.0",
        "react": "^0.14.0 || ^15.0.0-0"
    },
    "dependencies": {
        "collapse-white-space": "^1.0.0",
        "react-addons-test-utils": "^15.0.1",
        "react-element-to-jsx-string": "^2.5.0"
    },
    "devDependencies": {
        "babel-cli": "^6.1.2",
        "babel-core": "^6.1.2",
        "babel-eslint": "^4.1.4",
        "babel-loader": "^6.1.0",
        "babel-plugin-transform-class-properties": "^6.0.14",
        "babel-preset-es2015": "^6.1.2",
        "babel-preset-es2015-loose": "^6.1.2",
        "babel-preset-react": "^6.1.2",
        "chai": "^3.4.0",
        "chalk": "^1.1.1",
        "eslint": "^1.9.0",
        "eslint-config-ecliptic": "^1.2.1",
        "eslint-plugin-react": "^3.8.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.1.0",
        "gulp-sourcemaps": "^1.6.0",
        "istanbul": "^0.4.0",
        "mocha": "^2.3.3",
        "react": "^15.0.1",
        "webpack": "^1.12.3"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
