# test coverage for  [wd (v1.2.0)](https://github.com/admc/wd#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-wd.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wd) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wd.svg)](https://travis-ci.org/npmtest/node-npmtest-wd)
#### WebDriver/Selenium 2 node.js client

[![NPM](https://nodei.co/npm/wd.png?downloads=true)](https://www.npmjs.com/package/wd)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wd/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wd/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wd/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wd/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wd/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wd/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wd/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-wd/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-wd/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-wd/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-wd%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-wd/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wd/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-wd%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wd/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-wd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-wd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Adam Christian",
        "email": "adam.christian@gmail.com"
    },
    "bin": {
        "wd": "./lib/bin.js"
    },
    "bugs": {
        "url": "https://github.com/admc/wd/issues"
    },
    "contributors": [
        {
            "name": "Ruben Daniels",
            "url": "https://github.com/javruben"
        },
        {
            "name": "Peter Braden",
            "url": "https://github.com/peterbraden"
        },
        {
            "name": "Seb Vincent",
            "url": "https://github.com/sebv"
        },
        {
            "name": "Peter 'Pita' Martischka",
            "url": "https://github.com/Pita"
        },
        {
            "name": "Jonathan Lipps",
            "url": "https://github.com/jlipps"
        },
        {
            "name": "Phil Sarin",
            "url": "https://github.com/pdsarin"
        },
        {
            "name": "Mathieu Sabourin",
            "url": "https://github.com/OniOni"
        },
        {
            "name": "Bjorn Tipling",
            "url": "https://github.com/btipling"
        },
        {
            "name": "Santiago Suarez Ordonez",
            "url": "https://github.com/santiycr"
        },
        {
            "name": "Bernard Kobos",
            "url": "https://github.com/bernii"
        },
        {
            "name": "Jason Carr",
            "url": "https://github.com/maudineormsby"
        },
        {
            "name": "Matti Schneider",
            "email": "hi@mattischneider.fr",
            "url": "https://github.com/MattiSG"
        }
    ],
    "dependencies": {
        "archiver": "1.3.0",
        "async": "2.0.1",
        "lodash": "4.16.2",
        "mkdirp": "^0.5.1",
        "q": "1.4.1",
        "request": "2.79.0",
        "underscore.string": "3.3.4",
        "vargs": "0.1.0"
    },
    "description": "WebDriver/Selenium 2 node.js client",
    "devDependencies": {
        "bdd-with-opts": "1.1.1",
        "chai": "3.5.0",
        "chai-as-promised": "6.0.0",
        "colors": "1.1.2",
        "dox": "0.9.0",
        "express": "4.14.0",
        "gulp": "3.9.1",
        "gulp-jshint": "2.0.1",
        "hbs": "4.0.1",
        "http-proxy": "1.15.1",
        "imageinfo": "1.0.4",
        "istanbul": "0.4.5",
        "jshint": "2.9.3",
        "jshint-stylish": "2.2.1",
        "mocha": "3.1.0",
        "mu2": "0.5.21",
        "nock": "8.0.0",
        "promise-simple": "0.1.0",
        "run-sequence": "1.2.2",
        "sauce-connect-launcher": "0.16.0",
        "spawn-mocha-parallel": "1.3.1",
        "sv-selenium": "0.3.1",
        "uuid": "3.0.1",
        "yargs": "6.0.0"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "4112c4657eca5af593ebc060d54b80caeea04807",
        "tarball": "https://registry.npmjs.org/wd/-/wd-1.2.0.tgz"
    },
    "engines": [
        "node"
    ],
    "gitHead": "9e1c809e5830c16dea3aa80a9f47c58d9f4a973e",
    "homepage": "https://github.com/admc/wd#readme",
    "keywords": [
        "testing",
        "automation",
        "webdriver",
        "webdriverjs",
        "selenium"
    ],
    "license": "Apache-2.0",
    "main": "./lib/main",
    "maintainers": [
        {
            "name": "admc",
            "email": "adam.christian@gmail.com"
        },
        {
            "name": "sebv",
            "email": "seb.vincent@gmail.com"
        },
        {
            "name": "jlipps",
            "email": "jlipps@gmail.com"
        },
        {
            "name": "sourishkrout",
            "email": "sebastiantiedtke@gmail.com"
        }
    ],
    "name": "wd",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/admc/wd.git"
    },
    "scripts": {
        "all_tests": "gulp test",
        "install": "node scripts/build-browser-scripts",
        "test": "gulp test-unit"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
