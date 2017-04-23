# npmdoc-solr-client

#### api documentation for  [solr-client (v0.6.0)](https://github.com/lbdremy/solr-node-client#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-solr-client.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-solr-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-solr-client.svg)](https://travis-ci.org/npmdoc/node-npmdoc-solr-client)

####  A Solr client library for indexing, adding, deleting, committing, optimizing and searching documents within an Apache Solr installation (version>=3.2)

[![NPM](https://nodei.co/npm/solr-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/solr-client)

- [https://npmdoc.github.io/node-npmdoc-solr-client/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-solr-client/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-solr-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-solr-client/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-solr-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-solr-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Remy Loubradou",
        "url": "https://twitter.com/#!/lbdremy"
    },
    "bugs": {
        "url": "https://github.com/lbdremy/solr-node-client/issues"
    },
    "dependencies": {
        "JSONStream": "~1.0.6",
        "duplexer": "~0.1.1",
        "httperror": "~0.2.3",
        "json-bigint": "~0.1.4",
        "request": "~2.63.0"
    },
    "description": " A Solr client library for indexing, adding, deleting, committing, optimizing and searching documents within an Apache Solr installation (version>=3.2)",
    "devDependencies": {
        "bignumber.js": "~2.0.7",
        "chai": "~3.3.0",
        "csv-stream": "~0.1.3",
        "figc": "~0.0.3",
        "minimist": "~1.2.0",
        "mocha": "~2.3.3"
    },
    "directories": {},
    "dist": {
        "shasum": "c5cedb8b86e33abee992905c97b226574a490594",
        "tarball": "https://registry.npmjs.org/solr-client/-/solr-client-0.6.0.tgz"
    },
    "engines": {
        "node": ">= 0.4.7"
    },
    "gitHead": "41a9b5ecdeea41ea796ba4964d7dada1d4dfab38",
    "homepage": "https://github.com/lbdremy/solr-node-client#readme",
    "main": "./main",
    "maintainers": [
        {
            "name": "lbdremy"
        },
        {
            "name": "nicolasembleton"
        }
    ],
    "name": "solr-client",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lbdremy/solr-node-client.git"
    },
    "scripts": {
        "report": "rm -rf report && mkdir report && plato -r -d report main.js lib/*",
        "test": "./node_modules/mocha/bin/mocha -R spec test/*-test.js && ./node_modules/mocha/bin/mocha -R spec test/*-test.js --client.bigint=true",
        "test-cov": "jscoverage lib lib-cov && ./node_modules/mocha/bin/mocha -R html-cov test/*-test.js > coverage.html && rm -r lib-cov"
    },
    "version": "0.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
