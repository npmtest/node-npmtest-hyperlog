# npmtest-hyperlog

#### basic test coverage for  [hyperlog (v4.12.1)](https://github.com/mafintosh/hyperlog)  [![npm package](https://img.shields.io/npm/v/npmtest-hyperlog.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hyperlog) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hyperlog.svg)](https://travis-ci.org/npmtest/node-npmtest-hyperlog)

#### Merkle DAG that replicates based on scuttlebutt logs and causal linking

[![NPM](https://nodei.co/npm/hyperlog.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hyperlog)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hyperlog/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hyperlog/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hyperlog/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hyperlog/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hyperlog/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hyperlog/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hyperlog/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hyperlog/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hyperlog/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hyperlog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hyperlog/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hyperlog/build/test-report.html](https://npmtest.github.io/node-npmtest-hyperlog/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hyperlog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hyperlog/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hyperlog/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hyperlog/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hyperlog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hyperlog/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hyperlog/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hyperlog/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "hyperlog",
    "version": "4.12.1",
    "description": "Merkle DAG that replicates based on scuttlebutt logs and causal linking",
    "main": "index.js",
    "dependencies": {
        "after-all": "^2.0.2",
        "bitfield": "^1.1.2",
        "brfs": "^1.4.0",
        "cuid": "^1.2.5",
        "debug": "^2.2.0",
        "defined": "^1.0.0",
        "duplexify": "^3.4.2",
        "framed-hash": "^1.1.0",
        "from2": "^2.1.0",
        "length-prefixed-stream": "^1.3.0",
        "level-enumerate": "^1.0.1",
        "level-logs": "^1.1.0",
        "lexicographic-integer": "^1.1.0",
        "mutexify": "^1.1.0",
        "protocol-buffers": "^3.1.2",
        "pump": "^1.0.0",
        "run-parallel": "^1.1.6",
        "run-waterfall": "^1.1.3",
        "stream-collector": "^1.0.1",
        "through2": "^2.0.0"
    },
    "devDependencies": {
        "bs58": "^3.0.0",
        "memdb": "^1.0.1",
        "standard": "^5.0.0",
        "multihashing": "^0.2.0",
        "tape": "^4.0.0"
    },
    "browserify": {
        "transform": [
            "brfs"
        ]
    },
    "scripts": {
        "test": "standard && tape test/*"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/mafintosh/hyperlog.git"
    },
    "author": "Mathias Buus (@mafintosh)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/mafintosh/hyperlog/issues"
    },
    "homepage": "https://github.com/mafintosh/hyperlog"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
