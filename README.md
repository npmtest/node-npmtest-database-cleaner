# npmtest-database-cleaner

#### basic test coverage for  [database-cleaner (v1.2.0)](https://github.com/emerleite/node-database-cleaner#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-database-cleaner.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-database-cleaner) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-database-cleaner.svg)](https://travis-ci.org/npmtest/node-npmtest-database-cleaner)

#### Database Cleaner for node.js

[![NPM](https://nodei.co/npm/database-cleaner.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/database-cleaner)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-database-cleaner/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-database-cleaner/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-database-cleaner/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-database-cleaner/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-database-cleaner/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-database-cleaner/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-database-cleaner/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-database-cleaner/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-database-cleaner/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-database-cleaner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-database-cleaner/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-database-cleaner/build/test-report.html](https://npmtest.github.io/node-npmtest-database-cleaner/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-database-cleaner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-database-cleaner/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-database-cleaner/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-database-cleaner/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-database-cleaner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-database-cleaner/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-database-cleaner/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-database-cleaner/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Emerson Macedo"
    },
    "bugs": {
        "url": "https://github.com/emerleite/node-database-cleaner/issues"
    },
    "dependencies": {},
    "description": "Database Cleaner for node.js",
    "devDependencies": {
        "async": "1.5.0",
        "cradle": "0.5.8",
        "elasticsearch": "8.2.0",
        "lodash": "3.10.1",
        "mocha": "1.21.4",
        "mongodb": "2.1.10",
        "mysql": "2.5.1",
        "pg": "3.4.2",
        "redis": "0.12.1",
        "should": "4.0.4",
        "sqlite3": "3.1.6"
    },
    "directories": {},
    "dist": {
        "shasum": "0f756f1270e29bdd838dd8e989c7b22cca8ddd64",
        "tarball": "https://registry.npmjs.org/database-cleaner/-/database-cleaner-1.2.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "06199ac49cad762d590765439dedf3d9117940e9",
    "homepage": "https://github.com/emerleite/node-database-cleaner#readme",
    "keywords": [
        "database",
        "cleaner",
        "mongodb",
        "redis",
        "couchdb",
        "tests",
        "package.json",
        "elasticsearch"
    ],
    "main": "index",
    "maintainers": [
        {
            "name": "emerleite"
        }
    ],
    "name": "database-cleaner",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/emerleite/node-database-cleaner.git"
    },
    "scripts": {
        "test": "node_modules/mocha/bin/mocha -R spec --timeout 5000 --globals config,currentObjectStored"
    },
    "version": "1.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
