# Laravel OpenSearch

[中文说明](https://github.com/homesheer/laravel-opensearch/blob/master/README_CN.md)

[![For Laravel 5](https://img.shields.io/badge/laravel-5.*-green.svg)](https://github.com/laravel/laravel)
[![For Lumen 5](https://img.shields.io/badge/lumen-5.*-green.svg)](https://github.com/laravel/lumen)
[![Latest Version on Packagist](https://img.shields.io/packagist/v/homesheer/laravel-opensearch.svg)](https://packagist.org/packages/homesheer/laravel-opensearch)
[![Total Downloads](https://img.shields.io/packagist/dt/homesheer/laravel-opensearch.svg)](https://packagist.org/packages/homesheer/laravel-opensearch)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE)

## Introduction


## Requirements
This package requires Laravel 5.4 or newer.

## Installation

You can install the package via Composer:

``` bash
composer require homesheer/laravel-opensearch
```

You can publish the config file with:

```bash
php artisan vendor:publish --provider="HomeSheer\OpenSearch\OpenSearchServiceProvider" --tag="config"
```

For Laravel 5.4 or older:

```php
// config/app.php
HomeSheer\OpenSearch\OpenSearchServiceProvider::class,
```

For Lumen:

```php
// bootstrap/app.php
$app->register(HomeSheer\OpenSearch\OpenSearchProvider::class);
```

## Usage

    
## Contributing

Contributions are welcome, [thanks to y'all](https://github.com/homesheer/laravel-opensearch/graphs/contributors) :)

## License

Laravel Assembler is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).