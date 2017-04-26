# npmtest-atmo

#### basic test coverage for  [atmo (v0.14.2)](https://github.com/Raathigesh/Atmo)  [![npm package](https://img.shields.io/npm/v/npmtest-atmo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-atmo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-atmo.svg)](https://travis-ci.org/npmtest/node-npmtest-atmo)

#### Server side powertool for prototyping

[![NPM](https://nodei.co/npm/atmo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/atmo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-atmo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-atmo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-atmo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-atmo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-atmo/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-atmo/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-atmo/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-atmo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-atmo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-atmo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-atmo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-atmo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-atmo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-atmo/build/test-report.html](https://npmtest.github.io/node-npmtest-atmo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-atmo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-atmo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-atmo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-atmo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-atmo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-atmo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-atmo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-atmo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Raathigeshan Kugarajan"
    },
    "babel": {
        "presets": [
            "es2015-node5"
        ]
    },
    "bin": {
        "atmo": "bin/atmo"
    },
    "bugs": {
        "url": "https://github.com/Raathigesh/Atmo/issues"
    },
    "dependencies": {
        "apollo-server": "^0.1.2",
        "atmo-gen-expressjs-es5": "0.1.0",
        "body-parser": "1.15.2",
        "chalk": "^1.1.3",
        "express": "^4.13.4",
        "express-http-proxy": "^0.7.1",
        "figlet": "^1.1.2",
        "file-exists": "^1.0.0",
        "graphql": "^0.5.0",
        "json-server": "^0.8.14",
        "jsonfile": "^2.3.1",
        "morgan": "^1.7.0",
        "npmi": "^2.0.1",
        "server-destroy": "^1.0.1",
        "socket.io": "^1.4.5",
        "yargs": "^4.7.1"
    },
    "description": "Server side powertool for prototyping",
    "devDependencies": {
        "babel-cli": "^6.4.5",
        "babel-core": "^6.1.2",
        "babel-loader": "^6.0.1",
        "babel-plugin-transform-decorators-legacy": "^1.3.4",
        "babel-polyfill": "^6.9.1",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-es2015-node5": "^1.1.2",
        "babel-preset-react": "^6.1.2",
        "babel-preset-stage-1": "^6.5.0",
        "classnames": "^2.2.5",
        "css-loader": "^0.23.1",
        "file-loader": "^0.8.5",
        "jquery": "^2.2.3",
        "json-stringify-pretty-compact": "^1.0.1",
        "mobx": "^2.1.5",
        "mobx-react": "^3.0.5",
        "mobx-react-devtools": "^4.0.5",
        "nodemon": "^1.9.2",
        "react": "^0.14.0",
        "react-ace": "^3.4.0",
        "react-dom": "^0.14.0",
        "react-notification-system": "^0.2.7",
        "semantic-ui-css": "^2.1.8",
        "socket.io-client": "^1.4.5",
        "style-loader": "^0.13.1",
        "url-loader": "^0.5.7",
        "webpack": "^1.12.2",
        "webpack-dev-server": "^1.14.1"
    },
    "directories": {},
    "dist": {
        "shasum": "693749ce9541e0f7875bbff9ac5cfc5e16182f9e",
        "tarball": "https://registry.npmjs.org/atmo/-/atmo-0.14.2.tgz"
    },
    "gitHead": "090e3f9d4fa503ddddb1f5030c8e75f822792a47",
    "homepage": "https://github.com/Raathigesh/Atmo",
    "keywords": [
        "mock",
        "https",
        "socket",
        "socket.io",
        "graphql",
        "proxy",
        "httpProxy",
        "json-server",
        "prototype",
        "http-mock",
        "graphql-mock",
        "atmo"
    ],
    "license": "MIT",
    "main": "src/server/index.js",
    "maintainers": [
        {
            "name": "raathigesh"
        }
    ],
    "name": "atmo",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Raathigesh/Atmo.git"
    },
    "scripts": {
        "build": "webpack --config config/webpack.prod.config.js",
        "dev": "webpack-dev-server --config config/webpack.config.js --devtool eval --progress --colors --hot --content-base dist/",
        "server": "node ./src/server/index.js --static --port 8888",
        "start": "node ./src/server/index.js --static --port 8888"
    },
    "version": "0.14.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
