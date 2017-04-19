# npmtest-karma-coverage

#### test coverage for  [karma-coverage (v1.1.1)](https://github.com/karma-runner/karma-coverage#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-karma-coverage.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-karma-coverage) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-karma-coverage.svg)](https://travis-ci.org/npmtest/node-npmtest-karma-coverage)

#### A Karma plugin. Generate code coverage.

[![NPM](https://nodei.co/npm/karma-coverage.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/karma-coverage)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-karma-coverage/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-coverage/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-karma-coverage/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-karma-coverage/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-karma-coverage/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-karma-coverage/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-karma-coverage/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-karma-coverage/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-karma-coverage/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-coverage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-karma-coverage/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-karma-coverage/build/test-report.html](https://npmtest.github.io/node-npmtest-karma-coverage/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-karma-coverage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-karma-coverage/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-karma-coverage/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-karma-coverage/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-coverage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-coverage/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-karma-coverage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-karma-coverage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "SATO taichi"
    },
    "bugs": {
        "url": "https://github.com/karma-runner/karma-coverage/issues"
    },
    "contributors": [
        {
            "name": "dignifiedquire"
        },
        {
            "name": "Friedel Ziegelmayer"
        },
        {
            "name": "Aymeric Beaumet"
        },
        {
            "name": "Tim Kang"
        },
        {
            "name": "Nick Malaguti"
        },
        {
            "name": "Maksim Ryzhikov"
        },
        {
            "name": "Mark Ethan Trostler"
        },
        {
            "name": "nicojs"
        },
        {
            "name": "Allen Bierbaum"
        },
        {
            "name": "Douglas Duteil"
        },
        {
            "name": "Matt Winchester"
        },
        {
            "name": "Tanguy Krotoff"
        },
        {
            "name": "Wei Kin Huang"
        },
        {
            "name": "Kyle Welsby"
        },
        {
            "name": "Maciej Rzepiński"
        },
        {
            "name": "Joseph Connolly"
        },
        {
            "name": "Marceli.no"
        },
        {
            "name": "James Talmage"
        },
        {
            "name": "Mark Trostler"
        },
        {
            "name": "Matt Lewis"
        },
        {
            "name": "Chris Gladd"
        },
        {
            "name": "Michael Stramel"
        },
        {
            "name": "Greg Varsanyi"
        },
        {
            "name": "Nick Matantsev"
        },
        {
            "name": "Petar Manev"
        },
        {
            "name": "Robin Böhm"
        },
        {
            "name": "Ron Derksen"
        },
        {
            "name": "Ruben Bridgewater"
        },
        {
            "name": "Sahat Yalkabov"
        },
        {
            "name": "piecyk"
        },
        {
            "name": "Tanjo, Hiroyuki"
        },
        {
            "name": "Taylor Hakes"
        },
        {
            "name": "Dmitry Petrov"
        },
        {
            "name": "Timo Tijhof"
        },
        {
            "name": "Tom Kirkpatrick"
        },
        {
            "name": "Tyler Waters"
        },
        {
            "name": "Vincent Lemeunier"
        },
        {
            "name": "Dan Watling"
        },
        {
            "name": "terussell85"
        },
        {
            "name": "Yusuke Suzuki"
        },
        {
            "name": "aprooks"
        },
        {
            "name": "carlos"
        },
        {
            "name": "Clayton Watts"
        },
        {
            "name": "fbergr"
        },
        {
            "name": "Joshua Appelman"
        },
        {
            "name": "Julie"
        },
        {
            "name": "Lloyd Smith II"
        }
    ],
    "dependencies": {
        "dateformat": "^1.0.6",
        "istanbul": "^0.4.0",
        "lodash": "^3.8.0",
        "minimatch": "^3.0.0",
        "source-map": "^0.5.1"
    },
    "description": "A Karma plugin. Generate code coverage.",
    "devDependencies": {
        "chai": "^3.3.0",
        "eslint": "^2.2.0",
        "eslint-config-standard": "^5.1.0",
        "eslint-plugin-promise": "^1.1.0",
        "eslint-plugin-react": "^4.1.0",
        "eslint-plugin-standard": "^1.1.0",
        "grunt": "^0.4.1",
        "grunt-bump": "^0.7.0",
        "grunt-conventional-changelog": "^6.1.0",
        "grunt-conventional-github-releaser": "^1.0.0",
        "grunt-eslint": "^18.0.0",
        "grunt-karma": "1.x || ^0.12.0",
        "grunt-npm": "^0.0.2",
        "grunt-simple-mocha": "^0.4.0",
        "ibrik": "^2.0.0",
        "karma": "1.x || ^0.13.7",
        "karma-coffee-preprocessor": "1.x || ^0.3.0",
        "karma-firefox-launcher": "1.x || ^0.1.6",
        "karma-mocha": "1.x || ^0.2.0",
        "karma-requirejs": "1.x || ^0.2.2",
        "load-grunt-tasks": "^3.2.0",
        "mocha": "^2.2.5",
        "mocks": "0.0.15",
        "requirejs": "^2.1.20",
        "sinon": "^1.14.1",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5aff8b39cf6994dc22de4c84362c76001b637cf6",
        "tarball": "https://registry.npmjs.org/karma-coverage/-/karma-coverage-1.1.1.tgz"
    },
    "gitHead": "8b6ee3b006a20884309a15f6112952b633d07dbd",
    "homepage": "https://github.com/karma-runner/karma-coverage#readme",
    "keywords": [
        "karma-plugin",
        "karma-preprocessor",
        "karma-reporter",
        "coverage",
        "istanbul"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "vojtajina"
        },
        {
            "name": "zzo"
        },
        {
            "name": "dignifiedquire"
        }
    ],
    "name": "karma-coverage",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/karma-runner/karma-coverage.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
