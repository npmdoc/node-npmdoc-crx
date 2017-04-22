# npmdoc-crx

#### api documentation for  [crx (v3.2.1)](https://github.com/oncletom/crx)  [![npm package](https://img.shields.io/npm/v/npmdoc-crx.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-crx) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-crx.svg)](https://travis-ci.org/npmdoc/node-npmdoc-crx)

#### crx is a utility to package Google Chrome extensions via a Node API and the command line

[![NPM](https://nodei.co/npm/crx.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/crx)

- [https://npmdoc.github.io/node-npmdoc-crx/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-crx/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-crx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-crx/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-crx/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-crx/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jed Schmidt",
        "url": "http://jed.is"
    },
    "bin": {
        "crx": "./bin/crx.js"
    },
    "bugs": {
        "url": "https://github.com/oncletom/crx/issues"
    },
    "dependencies": {
        "archiver": "^1.1.0",
        "commander": "^2.5.0",
        "es6-promise": "^3.0.0",
        "node-rsa": "^0.2.10"
    },
    "description": "crx is a utility to package Google Chrome extensions via a Node API and the command line",
    "devDependencies": {
        "adm-zip": "^0.4.7",
        "github-changes": "^1.0.0",
        "nyc": "^8.3.0",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "17293ee75efdd08c6d1c8b3e1749d2d5757cf42b",
        "tarball": "https://registry.npmjs.org/crx/-/crx-3.2.1.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "d65dc24d340078e48f918b2ebff44b580a40291a",
    "homepage": "https://github.com/oncletom/crx",
    "license": "MIT",
    "main": "./src/crx.js",
    "maintainers": [
        {
            "name": "jed"
        },
        {
            "name": "oncletom"
        },
        {
            "name": "joscha"
        }
    ],
    "name": "crx",
    "nyc": {
        "functions": 100,
        "statements": 100,
        "branches": 100,
        "check-coverage": true,
        "reporter": [
            "text",
            "html"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/oncletom/crx.git"
    },
    "scripts": {
        "changelog": "github-changes -o oncletom -r crx -n ${npm_package_version}  --only-pulls --use-commit-body",
        "test": "nyc tape ./test/*.js",
        "version": "npm run changelog && git add CHANGELOG.md"
    },
    "version": "3.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
