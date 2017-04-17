# test coverage for  [dploy (v1.2.0)](https://github.com/LeanMeanFightingMachine/dploy)  [![npm package](https://img.shields.io/npm/v/npmtest-dploy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dploy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dploy.svg)](https://travis-ci.org/npmtest/node-npmtest-dploy)
#### Command line tool to deploy websites using FTP/SFTP and git.

[![NPM](https://nodei.co/npm/dploy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dploy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dploy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dploy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dploy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dploy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dploy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dploy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dploy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dploy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dploy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dploy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dploy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dploy/build/test-report.html](https://npmtest.github.io/node-npmtest-dploy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dploy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dploy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dploy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dploy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dploy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dploy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dploy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dploy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lucas Motta"
    },
    "bin": {
        "dploy": "./bin/dploy"
    },
    "bugs": {
        "url": "https://github.com/LeanMeanFightingMachine/dploy/issues"
    },
    "dependencies": {
        "colors": "~0.6.x",
        "ftp": "~0.3.x",
        "glob-expand": "0.0.2",
        "minimatch": "~0.2.x",
        "prompt": "~0.2.x",
        "signals": "~1.0.x",
        "ssh2": "~0.2.x",
        "yamljs": "~0.1.x"
    },
    "description": "Command line tool to deploy websites using FTP/SFTP and git.",
    "devDependencies": {
        "grunt": "~0.4.x",
        "grunt-bump": "~0.0.x",
        "grunt-coffeelint": "0.0.x",
        "grunt-contrib-coffee": "~0.7.x",
        "grunt-contrib-watch": "~0.5.x",
        "grunt-shell": "~0.6.x"
    },
    "directories": {},
    "dist": {
        "shasum": "69b32a507a6d76a4b93445d16c18ed45c93c4608",
        "tarball": "https://registry.npmjs.org/dploy/-/dploy-1.2.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.x"
    },
    "homepage": "https://github.com/LeanMeanFightingMachine/dploy",
    "keywords": [
        "ftp",
        "sftp",
        "deploy",
        "git"
    ],
    "main": "./lib/dploy",
    "maintainers": [
        {
            "name": "lucasmotta"
        }
    ],
    "name": "dploy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/LeanMeanFightingMachine/dploy.git"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
