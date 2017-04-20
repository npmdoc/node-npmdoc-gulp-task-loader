# npmdoc-gulp-task-loader

#### api documentation for  gulp-task-loader (v1.4.4)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-task-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-task-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-task-loader.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-task-loader)

#### Load gulp tasks from folder

[![NPM](https://nodei.co/npm/gulp-task-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-task-loader)

- [https://npmdoc.github.io/node-npmdoc-gulp-task-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-task-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-task-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-task-loader/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-task-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-task-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-task-loader",
    "repository": "https://github.com/hontas/gulp-task-loader.git",
    "version": "1.4.4",
    "description": "Load gulp tasks from folder",
    "main": "index.js",
    "scripts": {
        "major": "npm version major -m 'New major version %s' && npm publish",
        "minor": "npm version minor -m 'New minor version %s' && npm publish",
        "patch": "npm version patch -m 'New patch version %s' && npm publish",
        "postpublish": "git push --follow-tags",
        "test": "eslint . && mocha --reporter dot",
        "tdd": "npm run test -- --watch --reporter nyan"
    },
    "keywords": [
        "gulp",
        "task",
        "loader"
    ],
    "author": "Pontus Lundin",
    "license": "MIT",
    "peerDependencies": {
        "gulp": "*"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "coffee-script": "^1.10.0",
        "eslint": "^2.7.0",
        "gulp": "^3.9.1",
        "mocha": "^2.4.5"
    },
    "dependencies": {
        "object-assign": "^4.0.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
