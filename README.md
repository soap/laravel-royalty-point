# Laravel package to track royalty points

[![Latest Version on Packagist](https://img.shields.io/packagist/v/soap/laravel-royalty-point.svg?style=flat-square)](https://packagist.org/packages/soap/laravel-royalty-point)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/soap/laravel-royalty-point/run-tests?label=tests)](https://github.com/soap/laravel-royalty-point/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/workflow/status/soap/laravel-royalty-point/Check%20&%20fix%20styling?label=code%20style)](https://github.com/soap/laravel-royalty-point/actions?query=workflow%3A"Check+%26+fix+styling"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/soap/laravel-royalty-point.svg?style=flat-square)](https://packagist.org/packages/soap/laravel-royalty-point)

Small laravel package to tracking reward points and its redemption for Laravel Application. My first goal is to use in my tutorial application to track student point reward and usage.
- Daily student login reward.
- Student rewarded point on completion of videdo lesson.
- Student gains point from test score.
- Student can use point to pay for tuition fee.

## Support us


## Installation

You can install the package via composer:

```bash
composer require soap/laravel-royalty-point
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --tag="laravel-royalty-point-migrations"
php artisan migrate
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag="laravel-royalty-point-config"
```

This is the contents of the published config file:

```php
return [
];
```

Optionally, you can publish the views using

```bash
php artisan vendor:publish --tag="laravel-royalty-point-views"
```

## Usage

```php
$laravelRoyaltyPoint = new Soap\LaravelRoyaltyPoint();

```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](https://github.com/spatie/.github/blob/main/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Prasit Gebsaap](https://github.com/soap)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
