# npmtest-sqs-queue-parallel

#### basic test coverage for  [sqs-queue-parallel (v0.1.6)](https://github.com/bigluck/sqs-queue-parallel)  [![npm package](https://img.shields.io/npm/v/npmtest-sqs-queue-parallel.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sqs-queue-parallel) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sqs-queue-parallel.svg)](https://travis-ci.org/npmtest/node-npmtest-sqs-queue-parallel)

#### Create a poll of Amazon SQS queue watchers and each one can receive 1+ messages

[![NPM](https://nodei.co/npm/sqs-queue-parallel.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sqs-queue-parallel)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sqs-queue-parallel/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sqs-queue-parallel/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/test-report.html](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sqs-queue-parallel/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sqs-queue-parallel/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sqs-queue-parallel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sqs-queue-parallel/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sqs-queue-parallel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Luca Bigon"
    },
    "bugs": {
        "url": "https://github.com/bigluck/sqs-queue-parallel/issues"
    },
    "dependencies": {
        "async": "^0.2.10",
        "aws-sdk": "^2.0.0-rc11",
        "lodash": "^2.4.1"
    },
    "description": "Create a poll of Amazon SQS queue watchers and each one can receive 1+ messages",
    "devDependencies": {
        "coffee-script": "^1.7.1",
        "grunt": "^0.4.4",
        "grunt-banner": "^0.2.2",
        "grunt-contrib-coffee": "^0.10.1",
        "nodemon": "^1.0.15"
    },
    "directories": {},
    "dist": {
        "shasum": "260189a94aa0363a5746c57025f7f3e9004e19a5",
        "tarball": "https://registry.npmjs.org/sqs-queue-parallel/-/sqs-queue-parallel-0.1.6.tgz"
    },
    "gitHead": "6357cd5d49957418d0a57cf94fa401972276d151",
    "homepage": "https://github.com/bigluck/sqs-queue-parallel",
    "keywords": [
        "sqs",
        "queue",
        "poll",
        "amazon",
        "aws"
    ],
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/bigluck/sqs-queue-parallel/raw/master/LICENSE"
        }
    ],
    "main": "dist/sqs-queue-parallel",
    "maintainers": [
        {
            "name": "bigluck"
        }
    ],
    "name": "sqs-queue-parallel",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bigluck/sqs-queue-parallel.git"
    },
    "scripts": {
        "build": "grunt dist"
    },
    "version": "0.1.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
