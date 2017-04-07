# api documentation for  [react-masonry-component (v5.0.4)](https://github.com/eiriklv/react-masonry-component)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-masonry-component.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-masonry-component) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-masonry-component.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-masonry-component)
#### A masonry component for React.js

[![NPM](https://nodei.co/npm/react-masonry-component.png?downloads=true)](https://www.npmjs.com/package/react-masonry-component)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-masonry-component/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-masonry-component_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-masonry-component/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-masonry-component/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-masonry-component/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eirik Vullum",
        "email": "evullum@gmail.com",
        "url": "http://www.evconsult.no/"
    },
    "bugs": {
        "url": "https://github.com/eiriklv/react-masonry-component/issues"
    },
    "contributors": [
        {
            "name": "Marwan Butrous",
            "email": "marwan.butrous@protonmail.ch"
        }
    ],
    "dependencies": {
        "element-resize-detector": "^1.1.9",
        "imagesloaded": "^4.0.0",
        "lodash.assign": "^4.0.9",
        "lodash.debounce": "^4.0.6",
        "lodash.omit": "^4.3.0",
        "masonry-layout": "^4.0.0"
    },
    "description": "A masonry component for React.js",
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
        "react-addons-test-utils": "^15.4.0",
        "react-dom": "^15.4.1",
        "webpack": "^1.12.9"
    },
    "directories": {},
    "dist": {
        "shasum": "941e4a88567e6f461f725f81f294bd7051d15d30",
        "tarball": "https://registry.npmjs.org/react-masonry-component/-/react-masonry-component-5.0.4.tgz"
    },
    "gitHead": "de4b2585a1c3caf4272bfc74c82382826b6c2bda",
    "homepage": "https://github.com/eiriklv/react-masonry-component",
    "keywords": [
        "react",
        "mixin",
        "masonry",
        "packery",
        "isotope",
        "react-component"
    ],
    "license": "MIT",
    "main": "./lib/index",
    "maintainers": [
        {
            "name": "afram",
            "email": "marwan.butrous@protonmail.com"
        },
        {
            "name": "eiriklv",
            "email": "evullum@gmail.com"
        }
    ],
    "name": "react-masonry-component",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0-0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/eiriklv/react-masonry-component.git"
    },
    "scripts": {
        "dev": "karma start spec/setup/karma.conf.js --no-single-run",
        "lint": "eslint lib/index.js",
        "test": "npm run lint && karma start spec/setup/karma.conf.js"
    },
    "typings": "typings.d.ts",
    "version": "5.0.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-masonry-component](#apidoc.module.react-masonry-component)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.</span>default (props, context, updater)](#apidoc.element.react-masonry-component.default)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.</span>getDefaultProps ()](#apidoc.element.react-masonry-component.getDefaultProps)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.</span>propTypes.elementType ()](#apidoc.element.react-masonry-component.propTypes.elementType)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.</span>propTypes.enableResizableChildren ()](#apidoc.element.react-masonry-component.propTypes.enableResizableChildren)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.</span>propTypes.onImagesLoaded ()](#apidoc.element.react-masonry-component.propTypes.onImagesLoaded)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.</span>propTypes.options ()](#apidoc.element.react-masonry-component.propTypes.options)
1.  object <span class="apidocSignatureSpan">react-masonry-component.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-masonry-component.</span>propTypes
1.  string <span class="apidocSignatureSpan">react-masonry-component.</span>displayName

#### [module react-masonry-component.defaultProps](#apidoc.module.react-masonry-component.defaultProps)
1.  boolean <span class="apidocSignatureSpan">react-masonry-component.defaultProps.</span>disableImagesLoaded
1.  boolean <span class="apidocSignatureSpan">react-masonry-component.defaultProps.</span>enableResizableChildren
1.  boolean <span class="apidocSignatureSpan">react-masonry-component.defaultProps.</span>updateOnEachImageLoad
1.  [function <span class="apidocSignatureSpan">react-masonry-component.defaultProps.</span>onLayoutComplete ()](#apidoc.element.react-masonry-component.defaultProps.onLayoutComplete)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.defaultProps.</span>onRemoveComplete ()](#apidoc.element.react-masonry-component.defaultProps.onRemoveComplete)
1.  object <span class="apidocSignatureSpan">react-masonry-component.defaultProps.</span>options
1.  string <span class="apidocSignatureSpan">react-masonry-component.defaultProps.</span>className
1.  string <span class="apidocSignatureSpan">react-masonry-component.defaultProps.</span>elementType

#### [module react-masonry-component.propTypes](#apidoc.module.react-masonry-component.propTypes)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>disableImagesLoaded ()](#apidoc.element.react-masonry-component.propTypes.disableImagesLoaded)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>elementType ()](#apidoc.element.react-masonry-component.propTypes.elementType)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>enableResizableChildren ()](#apidoc.element.react-masonry-component.propTypes.enableResizableChildren)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>onImagesLoaded ()](#apidoc.element.react-masonry-component.propTypes.onImagesLoaded)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>onLayoutComplete ()](#apidoc.element.react-masonry-component.propTypes.onLayoutComplete)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>onRemoveComplete ()](#apidoc.element.react-masonry-component.propTypes.onRemoveComplete)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>options ()](#apidoc.element.react-masonry-component.propTypes.options)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>updateOnEachImageLoad ()](#apidoc.element.react-masonry-component.propTypes.updateOnEachImageLoad)

#### [module react-masonry-component.propTypes.elementType](#apidoc.module.react-masonry-component.propTypes.elementType)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>elementType ()](#apidoc.element.react-masonry-component.propTypes.elementType.elementType)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.elementType.</span>isRequired ()](#apidoc.element.react-masonry-component.propTypes.elementType.isRequired)

#### [module react-masonry-component.propTypes.enableResizableChildren](#apidoc.module.react-masonry-component.propTypes.enableResizableChildren)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>enableResizableChildren ()](#apidoc.element.react-masonry-component.propTypes.enableResizableChildren.enableResizableChildren)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.enableResizableChildren.</span>isRequired ()](#apidoc.element.react-masonry-component.propTypes.enableResizableChildren.isRequired)

#### [module react-masonry-component.propTypes.onImagesLoaded](#apidoc.module.react-masonry-component.propTypes.onImagesLoaded)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>onImagesLoaded ()](#apidoc.element.react-masonry-component.propTypes.onImagesLoaded.onImagesLoaded)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.onImagesLoaded.</span>isRequired ()](#apidoc.element.react-masonry-component.propTypes.onImagesLoaded.isRequired)

#### [module react-masonry-component.propTypes.options](#apidoc.module.react-masonry-component.propTypes.options)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>options ()](#apidoc.element.react-masonry-component.propTypes.options.options)
1.  [function <span class="apidocSignatureSpan">react-masonry-component.propTypes.options.</span>isRequired ()](#apidoc.element.react-masonry-component.propTypes.options.isRequired)



# <a name="apidoc.module.react-masonry-component"></a>[module react-masonry-component](#apidoc.module.react-masonry-component)

#### <a name="apidoc.element.react-masonry-component.default"></a>[function <span class="apidocSignatureSpan">react-masonry-component.</span>default (props, context, updater)](#apidoc.element.react-masonry-component.default)
- description and source-code
```javascript
default = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.getDefaultProps"></a>[function <span class="apidocSignatureSpan">react-masonry-component.</span>getDefaultProps ()](#apidoc.element.react-masonry-component.getDefaultProps)
- description and source-code
```javascript
getDefaultProps = function () {
  return {
    enableResizableChildren: false,
    disableImagesLoaded: false,
    updateOnEachImageLoad: false,
    options: {},
    className: '',
    elementType: 'div',
    onLayoutComplete: function() {
    },
    onRemoveComplete: function() {
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.elementType"></a>[function <span class="apidocSignatureSpan">react-masonry-component.</span>propTypes.elementType ()](#apidoc.element.react-masonry-component.propTypes.elementType)
- description and source-code
```javascript
propTypes.elementType = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.enableResizableChildren"></a>[function <span class="apidocSignatureSpan">react-masonry-component.</span>propTypes.enableResizableChildren ()](#apidoc.element.react-masonry-component.propTypes.enableResizableChildren)
- description and source-code
```javascript
propTypes.enableResizableChildren = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.onImagesLoaded"></a>[function <span class="apidocSignatureSpan">react-masonry-component.</span>propTypes.onImagesLoaded ()](#apidoc.element.react-masonry-component.propTypes.onImagesLoaded)
- description and source-code
```javascript
propTypes.onImagesLoaded = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.options"></a>[function <span class="apidocSignatureSpan">react-masonry-component.</span>propTypes.options ()](#apidoc.element.react-masonry-component.propTypes.options)
- description and source-code
```javascript
propTypes.options = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-masonry-component.defaultProps"></a>[module react-masonry-component.defaultProps](#apidoc.module.react-masonry-component.defaultProps)

#### <a name="apidoc.element.react-masonry-component.defaultProps.onLayoutComplete"></a>[function <span class="apidocSignatureSpan">react-masonry-component.defaultProps.</span>onLayoutComplete ()](#apidoc.element.react-masonry-component.defaultProps.onLayoutComplete)
- description and source-code
```javascript
onLayoutComplete = function () {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.defaultProps.onRemoveComplete"></a>[function <span class="apidocSignatureSpan">react-masonry-component.defaultProps.</span>onRemoveComplete ()](#apidoc.element.react-masonry-component.defaultProps.onRemoveComplete)
- description and source-code
```javascript
onRemoveComplete = function () {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-masonry-component.propTypes"></a>[module react-masonry-component.propTypes](#apidoc.module.react-masonry-component.propTypes)

#### <a name="apidoc.element.react-masonry-component.propTypes.disableImagesLoaded"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>disableImagesLoaded ()](#apidoc.element.react-masonry-component.propTypes.disableImagesLoaded)
- description and source-code
```javascript
disableImagesLoaded = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.elementType"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>elementType ()](#apidoc.element.react-masonry-component.propTypes.elementType)
- description and source-code
```javascript
elementType = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.enableResizableChildren"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>enableResizableChildren ()](#apidoc.element.react-masonry-component.propTypes.enableResizableChildren)
- description and source-code
```javascript
enableResizableChildren = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.onImagesLoaded"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>onImagesLoaded ()](#apidoc.element.react-masonry-component.propTypes.onImagesLoaded)
- description and source-code
```javascript
onImagesLoaded = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.onLayoutComplete"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>onLayoutComplete ()](#apidoc.element.react-masonry-component.propTypes.onLayoutComplete)
- description and source-code
```javascript
onLayoutComplete = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.onRemoveComplete"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>onRemoveComplete ()](#apidoc.element.react-masonry-component.propTypes.onRemoveComplete)
- description and source-code
```javascript
onRemoveComplete = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.options"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>options ()](#apidoc.element.react-masonry-component.propTypes.options)
- description and source-code
```javascript
options = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.updateOnEachImageLoad"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>updateOnEachImageLoad ()](#apidoc.element.react-masonry-component.propTypes.updateOnEachImageLoad)
- description and source-code
```javascript
updateOnEachImageLoad = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-masonry-component.propTypes.elementType"></a>[module react-masonry-component.propTypes.elementType](#apidoc.module.react-masonry-component.propTypes.elementType)

#### <a name="apidoc.element.react-masonry-component.propTypes.elementType.elementType"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>elementType ()](#apidoc.element.react-masonry-component.propTypes.elementType.elementType)
- description and source-code
```javascript
elementType = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.elementType.isRequired"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.elementType.</span>isRequired ()](#apidoc.element.react-masonry-component.propTypes.elementType.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-masonry-component.propTypes.enableResizableChildren"></a>[module react-masonry-component.propTypes.enableResizableChildren](#apidoc.module.react-masonry-component.propTypes.enableResizableChildren)

#### <a name="apidoc.element.react-masonry-component.propTypes.enableResizableChildren.enableResizableChildren"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>enableResizableChildren ()](#apidoc.element.react-masonry-component.propTypes.enableResizableChildren.enableResizableChildren)
- description and source-code
```javascript
enableResizableChildren = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.enableResizableChildren.isRequired"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.enableResizableChildren.</span>isRequired ()](#apidoc.element.react-masonry-component.propTypes.enableResizableChildren.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-masonry-component.propTypes.onImagesLoaded"></a>[module react-masonry-component.propTypes.onImagesLoaded](#apidoc.module.react-masonry-component.propTypes.onImagesLoaded)

#### <a name="apidoc.element.react-masonry-component.propTypes.onImagesLoaded.onImagesLoaded"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>onImagesLoaded ()](#apidoc.element.react-masonry-component.propTypes.onImagesLoaded.onImagesLoaded)
- description and source-code
```javascript
onImagesLoaded = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.onImagesLoaded.isRequired"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.onImagesLoaded.</span>isRequired ()](#apidoc.element.react-masonry-component.propTypes.onImagesLoaded.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-masonry-component.propTypes.options"></a>[module react-masonry-component.propTypes.options](#apidoc.module.react-masonry-component.propTypes.options)

#### <a name="apidoc.element.react-masonry-component.propTypes.options.options"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.</span>options ()](#apidoc.element.react-masonry-component.propTypes.options.options)
- description and source-code
```javascript
options = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-masonry-component.propTypes.options.isRequired"></a>[function <span class="apidocSignatureSpan">react-masonry-component.propTypes.options.</span>isRequired ()](#apidoc.element.react-masonry-component.propTypes.options.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
