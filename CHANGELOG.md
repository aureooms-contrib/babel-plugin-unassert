## [3.1.0](https://github.com/unassert-js/babel-plugin-unassert/releases/tag/v3.1.0) (2021-05-11)


#### Features

* [Add support for `node:` protocol require/import](https://github.com/unassert-js/babel-plugin-unassert/pull/11) by [@make-github-pseudonymous-again](https://github.com/make-github-pseudonymous-again)


### [3.0.1](https://github.com/unassert-js/babel-plugin-unassert/releases/tag/v3.0.1) (2019-05-14)


#### Bug Fixes

* [dealing with ESM import with ImportSpecifier](https://github.com/unassert-js/babel-plugin-unassert/pull/10) (Thanks [@fschopp](https://github.com/fschopp) for reporting and suggestion)


## [3.0.0](https://github.com/unassert-js/babel-plugin-unassert/releases/tag/v3.0.0) (2019-01-15)


#### Features

* Babel7 support


#### Breaking Changes

* Babel7 is incompatible with Babel6

For Babel6, you need to use [the 2.x release of babel-plugin-unassert](https://github.com/unassert-js/babel-plugin-unassert/tree/2.x).

```
$ npm install --save-dev babel-plugin-unassert@2
```


## [2.2.0](https://github.com/unassert-js/babel-plugin-unassert/releases/tag/v2.2.0) (2019-01-12)


#### Features

* [Support "Strict mode"](https://github.com/unassert-js/babel-plugin-unassert/pull/7)


### [2.1.2](https://github.com/unassert-js/babel-plugin-unassert/releases/tag/v2.1.2) (2016-12-24)


#### Chore

* transfer to unassert-js organization ([b2a95e9](https://github.com/unassert-js/babel-plugin-unassert/commit/b2a95e9eba65a16a86924d53fd63aa4d2ab341ad))


### [2.1.1](https://github.com/unassert-js/babel-plugin-unassert/releases/tag/v2.1.1) (2016-07-18)


#### Bug Fixes

* [Replace assertion with EmptyStatement if it is not a grandchild of BlockStatement](https://github.com/unassert-js/babel-plugin-unassert/pull/5)


## [2.1.0](https://github.com/unassert-js/babel-plugin-unassert/releases/tag/v2.1.0) (2016-04-28)


#### Features

* [Support ImportNamespaceSpecifier](https://github.com/unassert-js/babel-plugin-unassert/pull/4)


### [2.0.1](https://github.com/unassert-js/babel-plugin-unassert/releases/tag/v2.0.1) (2016-01-09)


#### Bug Fixes

* remove unnecessary dependencies ([bb28b466](https://github.com/unassert-js/babel-plugin-unassert/commit/bb28b4666de0ffdf7c86f78f03a35ef1372e1d1c))


## [2.0.0](https://github.com/unassert-js/babel-plugin-unassert/releases/tag/v2.0.0) (2015-11-07)


#### Features

* [Babel 6.x support](https://github.com/unassert-js/babel-plugin-unassert/pull/2)


#### Breaking Changes

* Babel6 is incompatible with Babel5. For Babel5 or lower, you need to use the 1.2.x release of babel-plugin-unassert.

```
$ npm install --save-dev babel-plugin-unassert@1.2.0
```


## [1.2.0](https://github.com/unassert-js/babel-plugin-unassert/releases/tag/v1.2.0) (2015-10-03)


#### Features

* support removal of assert variable assignment ([bf45e49d](https://github.com/unassert-js/babel-plugin-unassert/commit/bf45e49d73be3edc51f512a55ae11153ba41c697))


## [1.1.0](https://github.com/unassert-js/babel-plugin-unassert/releases/tag/v1.1.0) (2015-07-17)


#### Features

* [support removal of assert variable declaration](https://github.com/unassert-js/babel-plugin-unassert/pull/1)


### [1.0.1](https://github.com/unassert-js/babel-plugin-unassert/releases/tag/v1.0.1) (2015-07-13)


#### Bug Fixes

* dealing with rename in babel API (Path#remove to Path#dangerouslyRemove) ([c67e4de2](https://github.com/unassert-js/babel-plugin-unassert/commit/c67e4de289d7a0ac3330e1d26821dd965b651978))


## [1.0.0](https://github.com/unassert-js/babel-plugin-unassert/releases/tag/v1.0.0) (2015-05-26)


The first release.
