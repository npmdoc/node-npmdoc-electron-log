# npmdoc-electron-log

#### api documentation for  [electron-log (v2.2.2)](https://github.com/megahertz/electron-log#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-electron-log.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-electron-log) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-electron-log.svg)](https://travis-ci.org/npmdoc/node-npmdoc-electron-log)

#### Just a very simple logging module for your Electron application

[![NPM](https://nodei.co/npm/electron-log.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-log)

- [https://npmdoc.github.io/node-npmdoc-electron-log/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-log/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-log/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-log/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-electron-log/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-electron-log/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alexey Prokhorov"
    },
    "bugs": {
        "url": "https://github.com/megahertz/electron-log/issues"
    },
    "dependencies": {},
    "description": "Just a very simple logging module for your Electron application",
    "devDependencies": {
        "chai": "*",
        "jscs": "*",
        "jshint": "*",
        "jshint-reporter-jscs": "*",
        "mocha": "*",
        "rewire": "*",
        "tslint": "*",
        "typescript": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "cea73ed05fecf7614955c503d15bc78e92338f38",
        "tarball": "https://registry.npmjs.org/electron-log/-/electron-log-2.2.2.tgz"
    },
    "files": [
        "index.js",
        "main.js",
        "renderer.js",
        "lib/**/*.js",
        "!lib/**/*.spec.js",
        "electron-log.d.ts"
    ],
    "gitHead": "7129245bbb254d3861e36f829441748be1e51dec",
    "homepage": "https://github.com/megahertz/electron-log#readme",
    "keywords": [
        "electron",
        "atom",
        "log",
        "logger",
        "logging",
        "windows",
        "mac",
        "osx",
        "linux",
        "desktop"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "megahertz"
        }
    ],
    "name": "electron-log",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/megahertz/electron-log.git"
    },
    "scripts": {
        "jscs": "jscs .",
        "jshint": "jshint --exclude ./node_modules,./test-projects . --verbose",
        "mocha": "mocha index.spec.js lib/{,**/}{,**/}*.spec.js",
        "test": "npm run jshint && npm run jscs && npm run tslint && npm run mocha && npm run test-projects",
        "test-projects": "mocha test-projects/**/*.spec.js",
        "test-projects-install": "node test-projects/install.js",
        "tslint": "tslint electron-log.d.ts"
    },
    "typings": "./electron-log.d.ts",
    "version": "2.2.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
