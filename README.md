# npmtest-alexa-app-server

#### test coverage for  [alexa-app-server (v3.0.1)](https://github.com/alexa-js/alexa-app-server#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-alexa-app-server.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-alexa-app-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-alexa-app-server.svg)](https://travis-ci.org/npmtest/node-npmtest-alexa-app-server)

#### A web server module for Alexa (Amazon Echo) apps (skills) using Node.js, Express, and alexa-app.

[![NPM](https://nodei.co/npm/alexa-app-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/alexa-app-server)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-alexa-app-server/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-alexa-app-server/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-alexa-app-server/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-alexa-app-server/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-alexa-app-server/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-alexa-app-server/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-alexa-app-server/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-alexa-app-server/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-alexa-app-server/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-alexa-app-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-alexa-app-server/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-alexa-app-server/build/test-report.html](https://npmtest.github.io/node-npmtest-alexa-app-server/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-alexa-app-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-alexa-app-server/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-alexa-app-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-alexa-app-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-alexa-app-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-alexa-app-server/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-alexa-app-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-alexa-app-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt Kruse"
    },
    "bugs": {
        "url": "https://github.com/alexa-js/alexa-app-server/issues"
    },
    "dependencies": {
        "alexa-app": "^3.2.0",
        "bluebird": "^3.4.7",
        "body-parser": "~1.16.0",
        "ejs": "~2.5.5",
        "express": "~4.14.1",
        "hotswap": "^1.1.0",
        "lodash.defaults": "^4.2.0"
    },
    "description": "A web server module for Alexa (Amazon Echo) apps (skills) using Node.js, Express, and alexa-app.",
    "devDependencies": {
        "chai": "^3.5.0",
        "coveralls": "^2.11.15",
        "danger": "0.11.4",
        "istanbul": "0.4.5",
        "mocha": "^3.2.0",
        "sinon": "^1.17.7",
        "sinon-chai": "^2.8.0",
        "supertest": "^3.0.0",
        "tcp-port-used": "0.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "5fe1cc4b9bda291a7da795f2bcb862415259082f",
        "tarball": "https://registry.npmjs.org/alexa-app-server/-/alexa-app-server-3.0.1.tgz"
    },
    "gitHead": "6aac5665d4b1f3f82444cc10fe79d249b0787829",
    "homepage": "https://github.com/alexa-js/alexa-app-server#readme",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "dblock"
        },
        {
            "name": "mkruse"
        },
        {
            "name": "rickwargo"
        },
        {
            "name": "tejashah88"
        }
    ],
    "name": "alexa-app-server",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/alexa-js/alexa-app-server.git"
    },
    "scripts": {
        "coverage": "istanbul cover ./node_modules/.bin/_mocha -- -R spec",
        "coverage_local": "istanbul cover node_modules/mocha/bin/_mocha",
        "danger": "danger",
        "test": "mocha"
    },
    "version": "3.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
