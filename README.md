# Laravel Lodash

[![Build Status](https://img.shields.io/travis/akalongman/laravel-lodash/master.svg?style=flat-square)](https://travis-ci.org/akalongman/laravel-lodash)
[![Code Coverage](https://img.shields.io/scrutinizer/coverage/g/akalongman/laravel-lodash.svg?style=flat-square)](https://scrutinizer-ci.com/g/akalongman/laravel-lodash/?branch=master)
[![Code Quality](https://img.shields.io/scrutinizer/g/akalongman/laravel-lodash.svg?style=flat-square)](https://scrutinizer-ci.com/g/akalongman/laravel-lodash/?branch=master)
[![Latest Stable Version](https://img.shields.io/github/release/akalongman/laravel-lodash.svg?style=flat-square)](https://github.com/akalongman/laravel-lodash/releases)
[![Total Downloads](https://img.shields.io/packagist/dt/Longman/laravel-lodash.svg)](https://packagist.org/packages/longman/laravel-lodash)
[![Downloads Month](https://img.shields.io/packagist/dm/Longman/laravel-lodash.svg)](https://packagist.org/packages/longman/laravel-lodash)
[![License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)

This package adds lot of useful functionality to the Laravel project

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
    - [Commands](#commands)
    - [Functional](#functional)
- [TODO](#todo)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

## Installation

Install this package through [Composer](https://getcomposer.org/).

Edit your project's `composer.json` file to require `longman/laravel-lodash`

Create *composer.json* file:
```json
{
    "name": "yourproject/yourproject",
    "type": "project",
    "require": {
        "longman/laravel-lodash": "~0.0.1"
    }
}
```
And run composer update

**Or** run a command in your command line:

    composer require longman/laravel-lodash

Copy the package config to your local config with the publish command:

    php artisan vendor:publish --provider="Longman\LaravelLodash\LaravelLodashServiceProvider"


## Usage

### Commands

Command  | Description
------------- | -------------
`php artisan clear-all`  |  Clear entire cache and all cached routes, views, etc.


### Middlewares

Middleware  | Description
------------- | -------------
`AllowCorsRequests`  |  Allows cross origin requests. You can configure allowed hosts, methods and headers in the configuration file


### Functional



## TODO

write more tests

## Troubleshooting

If you like living on the edge, please report any bugs you find on the
[laravel-lodash issues](https://github.com/akalongman/laravel-lodash/issues) page.

## Contributing

Pull requests are welcome.
See [CONTRIBUTING.md](CONTRIBUTING.md) for information.

## License

Please see the [LICENSE](LICENSE.md) included in this repository for a full copy of the MIT license,
which this project is licensed under.

## Credits

- [Avtandil Kikabidze aka LONGMAN](https://github.com/akalongman)

Full credit list in [CREDITS](CREDITS)
