# npmtest-node-gitlab

#### test coverage for  [node-gitlab (v1.6.0)](https://github.com/repo-utils/gitlab)  [![npm package](https://img.shields.io/npm/v/npmtest-node-gitlab.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-gitlab) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-gitlab.svg)](https://travis-ci.org/npmtest/node-npmtest-node-gitlab)

#### Gitlab API nodejs client.

[![NPM](https://nodei.co/npm/node-gitlab.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-gitlab)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-gitlab/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-gitlab/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-gitlab/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-gitlab/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-gitlab/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-gitlab/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-gitlab/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-gitlab/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-gitlab/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-gitlab/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-gitlab/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-gitlab/build/test-report.html](https://npmtest.github.io/node-npmtest-node-gitlab/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-gitlab/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-gitlab/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-gitlab/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-gitlab/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-gitlab/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-gitlab/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-gitlab/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-gitlab/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "fengmk2"
    },
    "bugs": {
        "url": "https://github.com/repo-utils/gitlab/issues"
    },
    "contributors": [
        {
            "name": "fengmk2",
            "url": "https://github.com/fengmk2"
        },
        {
            "name": "shigeru.nakajima",
            "url": "https://github.com/ledsun"
        },
        {
            "name": "vsviridov",
            "url": "https://github.com/vsviridov"
        },
        {
            "name": "jarradseers",
            "url": "https://github.com/jarradseers"
        },
        {
            "name": "Simon Wachter",
            "url": "https://github.com/swordofpain"
        },
        {
            "name": "Selva Ganesh",
            "url": "https://github.com/selvagsz"
        },
        {
            "name": "Ad Taylor",
            "url": "https://github.com/adtaylor"
        },
        {
            "name": "Did",
            "url": "https://github.com/dcolens"
        }
    ],
    "dependencies": {
        "any-promise": "^1.3.0",
        "debug": "~2.2.0",
        "restful-client": "~1.0.0",
        "thunkify-wrap": "~1.0.4"
    },
    "description": "Gitlab API nodejs client.",
    "devDependencies": {
        "autod": "*",
        "co-mocha": "*",
        "contributors": "*",
        "istanbul-harmony": "*",
        "mocha": "*",
        "objectid": "^3.2.1",
        "pedding": "~1.0.0",
        "should": "~6.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "9c14db253b935b0c2e2ff49dc4c83fa595a2ced0",
        "tarball": "https://registry.npmjs.org/node-gitlab/-/node-gitlab-1.6.0.tgz"
    },
    "gitHead": "762abedf8f54475db67f14d854af0ce84c4aac7b",
    "homepage": "https://github.com/repo-utils/gitlab",
    "keywords": [
        "gitlab",
        "gitlab api",
        "git"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fengmk2"
        },
        {
            "name": "dead-horse"
        },
        {
            "name": "dead_horse"
        }
    ],
    "name": "node-gitlab",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/repo-utils/gitlab.git"
    },
    "scripts": {
        "autod": "autod -w --prefix '~'",
        "cnpm": "npm install --registry=https://registry.npm.taobao.org",
        "contributors": "contributors -f plain -o AUTHORS",
        "jshint": "jshint .",
        "test": "mocha --harmony -R spec -r co-mocha -t 40000 test/*.test.js",
        "test-cov": "node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- -r co-mocha -t 40000 test/*.test.js",
        "test-travis": "node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha --report lcovonly -- -r co-mocha -t 40000 test/*.test.js"
    },
    "version": "1.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
