# npmtest-react-masonry-component

#### basic test coverage for  [react-masonry-component (v5.0.5)](https://github.com/eiriklv/react-masonry-component)  [![npm package](https://img.shields.io/npm/v/npmtest-react-masonry-component.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-masonry-component) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-masonry-component.svg)](https://travis-ci.org/npmtest/node-npmtest-react-masonry-component)

#### A masonry component for React.js

[![NPM](https://nodei.co/npm/react-masonry-component.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-masonry-component)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-masonry-component/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-masonry-component/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-masonry-component/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-masonry-component/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-masonry-component/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-masonry-component/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-masonry-component/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-masonry-component/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-masonry-component/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-masonry-component/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-masonry-component/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-masonry-component/build/test-report.html](https://npmtest.github.io/node-npmtest-react-masonry-component/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-masonry-component/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-masonry-component/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-masonry-component/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-masonry-component/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-masonry-component/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-masonry-component/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-masonry-component/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-masonry-component/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-masonry-component",
    "version": "5.0.5",
    "main": "./lib/index",
    "description": "A masonry component for React.js",
    "typings": "typings.d.ts",
    "dependencies": {
        "create-react-class": "^15.5.2",
        "element-resize-detector": "^1.1.9",
        "imagesloaded": "^4.0.0",
        "lodash.assign": "^4.0.9",
        "lodash.debounce": "^4.0.6",
        "lodash.omit": "^4.3.0",
        "masonry-layout": "^4.0.0",
        "prop-types": "^15.5.8"
    },
    "devDependencies": {
        "babel-core": "^6.3.26",
        "babel-loader": "^6.2.0",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.3.13",
        "eslint": "^3.13.0",
        "expect": "^1.13.4",
        "function-bind": "^1.0.2",
        "imports-loader": "^0.6.5",
        "karma": "^1.3.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-cli": "^0.1.2",
        "karma-mocha": "^0.2.1",
        "karma-phantomjs-launcher": "^1.0.2",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.8.1",
        "mocha": "^2.3.4",
        "phantomjs": "^1.9.19",
        "react": "^15.4.1",
        "react-dom": "^15.4.1",
        "webpack": "^1.12.9"
    },
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0-0"
    },
    "scripts": {
        "test": "npm run lint && karma start spec/setup/karma.conf.js",
        "dev": "karma start spec/setup/karma.conf.js --no-single-run",
        "lint": "eslint lib/index.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/eiriklv/react-masonry-component.git"
    },
    "keywords": [
        "react",
        "mixin",
        "masonry",
        "packery",
        "isotope",
        "react-component"
    ],
    "author": "Eirik Vullum <evullum@gmail.com> (http://www.evconsult.no/)",
    "contributors": [
        {
            "name": "Marwan Butrous"
        }
    ],
    "bugs": {
        "url": "https://github.com/eiriklv/react-masonry-component/issues"
    },
    "homepage": "https://github.com/eiriklv/react-masonry-component",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
