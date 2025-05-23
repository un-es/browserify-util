# util change log

## 0.12.6

### Patch Changes

- b5469a0: refactor!: remove and replace all unneeded polyfills

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](http://semver.org/).

## 0.12.5

- Move `safe-buffer` dependency to a dev-only dependency. ([@goto-bus-stop](https://github.com/goto-bus-stop) in [e84cfd5](https://github.com/browserify/node-util/commit/e84cfd5e4923631d012e578d7aa140412a475646))
- Document usage with webpack 5+. ([@MatrixFrog](https://github.com/MatrixFrog) in [#69](https://github.com/browserify/node-util/pull/69))

## 0.12.4

- Avoid SharedArrayBuffer until required. ([@snyamathi](https://github.com/snyamathi) in [#59](https://github.com/browserify/node-util/pull/59))

  This fixes a [security warning](https://developers.google.com/search/blog/2021/03/sharedarraybuffer-notes) for SharedArrayBuffer.

## 0.12.3

- Use robust `which-typed-array`, `is-typed-array` modules for the `util.types.isTypedArray` family of functions. ([@wbinnssmith](https://github.com/wbinnssmith) in [#47](https://github.com/browserify/node-util/pull/47))

  This fixes crash in IE11 when a polyfilled `Symbol` is available in the environment.

## 0.12.2

- Move `object.entries` dependency to a dev-only dependency. ([@goto-bus-stop](https://github.com/goto-bus-stop) in [622f036](https://github.com/browserify/node-util/commit/622f0361540997e7e7b8abcff9865b47b2fa658c))

## 0.12.1

- Update `util.debuglog` compatibility to Node 10.4.0. ([@goto-bus-stop](https://github.com/goto-bus-stop) in [#27](https://github.com/browserify/node-util/pull/27))
- Allow newer versions of `inherits`. ([@snyamathi](https://github.com/snyamathi) in [#39](https://github.com/browserify/node-util/pull/39))

## 0.12.0

- Add `util.types`. ([@lukechilds](https://github.com/lukechilds) in [#32](https://github.com/browserify/node-util/pull/35))

## 0.11.1

- Fix an infinite loop in `util.deprecate` some build configurations. ([@bernardmcmanus](https://github.com/bernardmcmanus) in [#12](https://github.com/browserify/node-util/pull/12))

## 0.11.0

- Add `util.promisify`.
- Add `util.callbackify`.

## 0.10.4

- Update `inherits` dependency.
