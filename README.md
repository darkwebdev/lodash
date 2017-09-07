# lodash v4.17.4

[Site](https://lodash.com/) |
[Docs](https://lodash.com/docs) |
[FP Guide](https://github.com/lodash/lodash/wiki/FP-Guide) |
[Contributing](https://github.com/lodash/lodash/blob/master/.github/CONTRIBUTING.md) |
[Wiki](https://github.com/lodash/lodash/wiki "Changelog, Roadmap, etc.") |
[Code of Conduct](https://js.foundation/community/code-of-conduct) |
[Twitter](https://twitter.com/bestiejs) |
[Chat](https://gitter.im/lodash/lodash)

The [Lodash](https://lodash.com/) library exported as a Node module omitting any outdated exports like AMD (which are incompatible with [Lasso](https://github.com/lasso-js/lasso) bundler).

Generated using [lodash-cli](https://www.npmjs.com/package/lodash-cli):
```shell
$ lodash exports=node -o lodash.js
```

Lodash is released under the [MIT license](https://raw.githubusercontent.com/lodash/lodash/4.17.4/LICENSE) & supports modern environments.<br>
Review the [build differences](https://github.com/lodash/lodash/wiki/build-differences) & pick one that’s right for you.

## Installation

Using yarn:
```shell
$ yarn add lodash-lasso
```

Using npm:
```shell
$ npm i --save lodash-lasso
```

In Node.js:
```js
// Load the full build.
var _ = require('lodash');
// Load the core build.
var _ = require('lodash/core');
// Load the FP build for immutable auto-curried iteratee-first data-last methods.
var fp = require('lodash/fp');

// Load method categories.
var array = require('lodash/array');
var object = require('lodash/fp/object');

// Cherry-pick methods for smaller browserify/rollup/webpack bundles.
var at = require('lodash/at');
var curryN = require('lodash/fp/curryN');
```

**Note:**<br>
Install [n_](https://www.npmjs.com/package/n_) for Lodash use in the Node.js < 6 REPL.

## Why Lodash?

Lodash makes JavaScript easier by taking the hassle out of working with arrays,<br>
numbers, objects, strings, etc. Lodash’s modular methods are great for:

 * Iterating arrays, objects, & strings
 * Manipulating & testing values
 * Creating composite functions

## Module Formats

Lodash is available in a [variety of builds](https://lodash.com/custom-builds) & module formats.

 * [lodash](https://www.npmjs.com/package/lodash) & [per method packages](https://www.npmjs.com/browse/keyword/lodash-modularized)
 * [lodash-es](https://www.npmjs.com/package/lodash-es), [babel-plugin-lodash](https://www.npmjs.com/package/babel-plugin-lodash), & [lodash-webpack-plugin](https://www.npmjs.com/package/lodash-webpack-plugin)
 * [lodash/fp](https://github.com/lodash/lodash/tree/npm/fp)
 * [lodash-amd](https://www.npmjs.com/package/lodash-amd)
