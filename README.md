# AngularJS ui-select [![Build Status](https://travis-ci.org/angular-ui/ui-select.svg?branch=master)](https://travis-ci.org/angular-ui/ui-select) [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/angular-ui/ui-select?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

AngularJS-native version of [Select2](http://ivaynberg.github.io/select2/) and [Selectize](http://brianreavis.github.io/selectize.js/). [http://angular-ui.github.io/ui-select/](http://angular-ui.github.io/ui-select/)

[Getting Started](https://github.com/angular-ui/ui-select/wiki/Getting-Started) 

- [Examples](http://angular-ui.github.io/ui-select/#examples)
- [Examples Source](./docs/examples)
- [Documentation](https://github.com/angular-ui/ui-select/wiki)

## Latest Changes

- Check [CHANGELOG.md](/CHANGELOG.md)

## Features

- Search, Select, Multi-select and Tagging
- Multiple Themes: Bootstrap, Select2 and Selectize
- Keyboard support
- No jQuery required (except for old browsers)
- Small code base: 4.57KB min/gzipped vs 20KB for select2

For the roadmap, check [issue #3](https://github.com/angular-ui/ui-select/issues/3) and the [Wiki page](https://github.com/angular-ui/ui-select/wiki/Roadmap).

## Installation Methods

### npm
```
$ npm install ct-ui-select
```

## Development

### Prepare your environment
* Install [Node.js](http://nodejs.org/) and NPM (should come with)
* Install global dev dependencies: `npm install -g gulp`
* Install local dev dependencies: `npm install` in repository directory

### Development Commands

* `npm run build` to jshint and build
* `npm run test` for one-time test with karma (also build and jshint)
* `npm run watch` to watch src files to jshint, build and test when changed
* `npm run docs` build docs and examples

## Contributing

- Check [CONTRIBUTING.md](/CONTRIBUTING.md)
- Run the tests
- Try the [examples](./docs/examples)

When issuing a pull request, please exclude changes from the "dist" folder to avoid merge conflicts.
