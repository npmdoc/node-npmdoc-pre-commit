# api documentation for  [pre-commit (v1.2.2)](https://github.com/observing/pre-commit)  [![npm package](https://img.shields.io/npm/v/npmdoc-pre-commit.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pre-commit) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pre-commit.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pre-commit)
#### Automatically install pre-commit hooks for your npm modules.

[![NPM](https://nodei.co/npm/pre-commit.png?downloads=true)](https://www.npmjs.com/package/pre-commit)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pre-commit/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-pre-commit_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pre-commit/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-pre-commit/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Arnout Kazemier",
        "email": "opensource@observe.it"
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
            "name": "swaagie",
            "email": "info@martijnswaagman.nl"
        },
        {
            "name": "3rdeden",
            "email": "npm@3rd-Eden.com"
        },
        {
            "name": "v1",
            "email": "info@3rd-Eden.com"
        }
    ],
    "name": "pre-commit",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
    "version": "1.2.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module pre-commit](#apidoc.module.pre-commit)
1.  object <span class="apidocSignatureSpan">pre-commit.</span>log



# <a name="apidoc.module.pre-commit"></a>[module pre-commit](#apidoc.module.pre-commit)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
