[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url] [![Coverage percentage][coveralls-image]][coveralls-url]

# Shopware CLI

Convinient CLI tool for Shopware - **BETA**

## Features

- Run Shopware console commands from any subdirectory in the project.
- Run the official [Shopware CLI tools](https://github.com/shopwareLabs/sw-cli-tools) from any subdirectory in the project.

## Install

```sh
$ npm i -g shopware-cli

# or

$ yarn global add shopware-cli
```

## Usage

#### Console

```sh
$ shopware console command [options] [arguments]
```

#### Official Shopware CLI tools

```sh
$ shopware tools command [options] [arguments]
```

#### Clear cache

```sh
$ shopware clear:cache [options]
```

## License

MIT © [Ben Zörb](http://sommerlaune.com)

[npm-image]: https://badge.fury.io/js/shopware-cli.svg
[npm-url]: https://npmjs.org/package/shopware-cli
[travis-image]: https://travis-ci.org/bezoerb/shopware-cli.svg?branch=master
[travis-url]: https://travis-ci.org/bezoerb/shopware-cli
[daviddm-image]: https://david-dm.org/bezoerb/shopware-cli.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/bezoerb/shopware-cli
[coveralls-image]: https://coveralls.io/repos/bezoerb/shopware-cli/badge.svg
[coveralls-url]: https://coveralls.io/r/bezoerb/shopware-cli
