# npmdoc-pre-commit

#### basic api documentation for  [pre-commit (v1.2.2)](https://github.com/observing/pre-commit)  [![npm package](https://img.shields.io/npm/v/npmdoc-pre-commit.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pre-commit) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pre-commit.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pre-commit)

#### Automatically install pre-commit hooks for your npm modules.

[![NPM](https://nodei.co/npm/pre-commit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pre-commit)

- [https://npmdoc.github.io/node-npmdoc-pre-commit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pre-commit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pre-commit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pre-commit/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pre-commit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pre-commit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arnout Kazemier"
    },
    "bugs": {
        "url": "https://github.com/observing/pre-commit/issues"
    },
    "dependencies": {
        "cross-spawn": "^5.0.1",
        "spawn-sync": "^1.0.15",
        "which": "1.2.x"
    },
    "description": "Automatically install pre-commit hooks for your npm modules.",
    "devDependencies": {
        "assume": "1.4.x",
        "istanbul": "0.4.x",
        "mocha": "~3.2.0",
        "pre-commit": "git://github.com/observing/pre-commit.git"
    },
    "directories": {},
    "dist": {
        "shasum": "dbcee0ee9de7235e57f79c56d7ce94641a69eec6",
        "tarball": "https://registry.npmjs.org/pre-commit/-/pre-commit-1.2.2.tgz"
    },
    "gitHead": "bf393adbf5de842b6286dc1d12d024fb2784d1f5",
    "homepage": "https://github.com/observing/pre-commit",
    "keywords": [
        "git",
        "hooks",
        "npm",
        "pre-commit",
        "precommit",
        "run",
        "test",
        "development"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "swaagie"
        },
        {
            "name": "3rdeden"
        },
        {
            "name": "v1"
        }
    ],
    "name": "pre-commit",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/observing/pre-commit.git"
    },
    "scripts": {
        "coverage": "istanbul cover ./node_modules/.bin/_mocha -- test.js",
        "example-fail": "echo \"This is the example hook, I exit with 1\" && exit 1",
        "example-pass": "echo \"This is the example hook, I exit with 0\" && exit 0",
        "install": "node install.js",
        "test": "mocha test.js",
        "test-travis": "istanbul cover node_modules/.bin/_mocha --report lcovonly -- test.js",
        "uninstall": "node uninstall.js"
    },
    "version": "1.2.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
