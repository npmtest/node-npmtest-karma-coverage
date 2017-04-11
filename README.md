# test coverage for  [karma-coverage (v1.1.1)](https://github.com/karma-runner/karma-coverage#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-karma-coverage.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-karma-coverage) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-karma-coverage.svg)](https://travis-ci.org/npmtest/node-npmtest-karma-coverage)
#### A Karma plugin. Generate code coverage.

[![NPM](https://nodei.co/npm/karma-coverage.png?downloads=true)](https://www.npmjs.com/package/karma-coverage)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-karma-coverage/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-coverage/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-karma-coverage/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-karma-coverage/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-karma-coverage/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-karma-coverage/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-karma-coverage/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-coverage/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-karma-coverage/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-karma-coverage/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-karma-coverage%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-karma-coverage/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-coverage/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-karma-coverage%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-coverage/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-karma-coverage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-karma-coverage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "SATO taichi",
        "email": "ryushi@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/karma-runner/karma-coverage/issues"
    },
    "contributors": [
        {
            "name": "dignifiedquire",
            "email": "dignifiedquire@gmail.com"
        },
        {
            "name": "Friedel Ziegelmayer",
            "email": "dignifiedquire@gmail.com"
        },
        {
            "name": "Aymeric Beaumet",
            "email": "aymeric@beaumet.me"
        },
        {
            "name": "Tim Kang",
            "email": "timkang@ucla.edu"
        },
        {
            "name": "Nick Malaguti",
            "email": "nmalaguti@palantir.com"
        },
        {
            "name": "Maksim Ryzhikov",
            "email": "rv.maksim@gmail.com"
        },
        {
            "name": "Mark Ethan Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "nicojs",
            "email": "jansennico@gmail.com"
        },
        {
            "name": "Allen Bierbaum",
            "email": "abierbaum@gmail.com"
        },
        {
            "name": "Douglas Duteil",
            "email": "douglasduteil@gmail.com"
        },
        {
            "name": "Matt Winchester",
            "email": "m_winche@yahoo.com"
        },
        {
            "name": "Tanguy Krotoff",
            "email": "tkrotoff@gmail.com"
        },
        {
            "name": "Wei Kin Huang",
            "email": "weikin.huang04@gmail.com"
        },
        {
            "name": "Kyle Welsby",
            "email": "kyle@mekyle.com"
        },
        {
            "name": "Maciej Rzepiński",
            "email": "maciej.rzepinski@gmail.com"
        },
        {
            "name": "Joseph Connolly",
            "email": "joec@avinetworks.com"
        },
        {
            "name": "Marceli.no",
            "email": "me@marceli.no"
        },
        {
            "name": "James Talmage",
            "email": "james@talmage.io"
        },
        {
            "name": "Mark Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "Matt Lewis",
            "email": "matthew.lewis@socialsignin.co.uk"
        },
        {
            "name": "Chris Gladd",
            "email": "chris.m.gladd@gmail.com"
        },
        {
            "name": "Michael Stramel",
            "email": "m.stramel89@gmail.com"
        },
        {
            "name": "Greg Varsanyi",
            "email": "gvarsanyi@gmail.com"
        },
        {
            "name": "Nick Matantsev",
            "email": "nick.matantsev@gmail.com"
        },
        {
            "name": "Petar Manev",
            "email": "petar.manev2010@gmail.com"
        },
        {
            "name": "Robin Böhm",
            "email": "robinboehm@googlemail.com"
        },
        {
            "name": "Ron Derksen",
            "email": "ron.derksen@informaat.nl"
        },
        {
            "name": "Ruben Bridgewater",
            "email": "ruben.bridgewater@fintura.de"
        },
        {
            "name": "Sahat Yalkabov",
            "email": "sakhat@gmail.com"
        },
        {
            "name": "piecyk",
            "email": "piecyk@gmail.com"
        },
        {
            "name": "Tanjo, Hiroyuki",
            "email": "expheno@gmail.com"
        },
        {
            "name": "Taylor Hakes",
            "email": "taylor@taylorhakes.com"
        },
        {
            "name": "Dmitry Petrov",
            "email": "dpetroff@gmail.com"
        },
        {
            "name": "Timo Tijhof",
            "email": "krinklemail@gmail.com"
        },
        {
            "name": "Tom Kirkpatrick",
            "email": "tom@systemseed.com"
        },
        {
            "name": "Tyler Waters",
            "email": "tyler.waters@gmail.com"
        },
        {
            "name": "Vincent Lemeunier",
            "email": "vincent.lemeunier+git@gmail.com"
        },
        {
            "name": "Dan Watling",
            "email": "dan@synaptik.com"
        },
        {
            "name": "terussell85",
            "email": "terussell85@gmail.com"
        },
        {
            "name": "Yusuke Suzuki",
            "email": "utatane.tea@gmail.com"
        },
        {
            "name": "aprooks",
            "email": "alexander.prooks@gmail.com"
        },
        {
            "name": "carlos",
            "email": "cafesanu@gmail.com"
        },
        {
            "name": "Clayton Watts",
            "email": "cletusw@gmail.com"
        },
        {
            "name": "fbergr",
            "email": "fbergr@gmail.com"
        },
        {
            "name": "Joshua Appelman",
            "email": "jappelman@xebia.com"
        },
        {
            "name": "Julie",
            "email": "ju.ralph@gmail.com"
        },
        {
            "name": "Lloyd Smith II",
            "email": "lloyd@trove.com"
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
            "name": "vojtajina",
            "email": "vojta.jina+npm@gmail.com"
        },
        {
            "name": "zzo",
            "email": "mark@zzo.com"
        },
        {
            "name": "dignifiedquire",
            "email": "dignifiedquire@gmail.com"
        }
    ],
    "name": "karma-coverage",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
