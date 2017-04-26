# Connecty API gateway

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE)

PHP Gateway for different API clients

## Install

Via Composer

``` bash
$ composer require secux/connecty
```

## Usage

``` php
// Create the gateway object
$gw = Connecty::create('MyGateway');
// Create the request object
$my_request = $gw->myRequest($request_params);
$response = $my_request->send();
```

## Change log
Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing
``` bash
$ composer test
```

## Credits
This project is forked from devTransition/php-connecty


[ico-version]: https://img.shields.io/packagist/v/secux/connecty.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-Apache-brightgreen.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/secux/connecty
