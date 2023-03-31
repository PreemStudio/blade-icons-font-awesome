# Font Awesome

[![Latest Version on Packagist](https://img.shields.io/packagist/v/preemstudio/blade-icons-font-awesome.svg?style=flat-square)](https://packagist.org/packages/preemstudio/blade-icons-font-awesome)
[![GitHub Tests Action Status](https://img.shields.io/github/actions/workflow/status/preemstudio/blade-icons-font-awesome/run-tests.yml?branch=main&label=tests&style=flat-square)](https://github.com/preemstudio/blade-icons-font-awesome/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/actions/workflow/status/preemstudio/blade-icons-font-awesome/fix-php-code-style-issues.yml?branch=main&label=code%20style&style=flat-square)](https://github.com/preemstudio/blade-icons-font-awesome/actions?query=workflow%3A"Fix+PHP+code+style+issues"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/preemstudio/blade-icons-font-awesome.svg?style=flat-square)](https://packagist.org/packages/preemstudio/blade-icons-font-awesome)

A package to easily make use of [Font Awesome](https://fontawesome.com/) in your Laravel Blade views.

## Installation

You can install the package via composer:

```bash
composer require preemstudio/blade-icons-font-awesome
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag=blade-icons-font-awesome-config
```

## Usage

This package utilizes Blade Icons under the hood. For additional functionality, please refer to the [Blade Icons README](https://github.com/PreemStudio/blade-icons). The prefix for all icons in this package is `font-awesome`, with specific sets available as `font-awesome-brands`, `font-awesome-regular`, and `font-awesome-solid`.

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security Vulnerabilities

If you've found a bug regarding security please mail [security@preem.studio](mailto:security@preem.studio) instead of using the issue tracker.

## Credits

- [Preem Studio](https://github.com/PreemStudio)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.