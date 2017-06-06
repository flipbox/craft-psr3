# PSR-3 Logger for Craft CMS
[![Latest Version](https://img.shields.io/github/release/flipbox/craft-psr3.svg?style=flat-square)](https://github.com/flipbox/craft-psr3/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/flipbox/craft-psr3/master.svg?style=flat-square)](https://travis-ci.org/flipbox/craft-psr3)
[![Coverage Status](https://img.shields.io/scrutinizer/coverage/g/flipbox/craft-psr3.svg?style=flat-square)](https://scrutinizer-ci.com/g/flipbox/craft-psr3/code-structure)
[![Quality Score](https://img.shields.io/scrutinizer/g/flipbox/craft-psr3.svg?style=flat-square)](https://scrutinizer-ci.com/g/flipbox/craft-psr3)
[![Total Downloads](https://img.shields.io/packagist/dt/flipboxdigital/craft-psr3.svg?style=flat-square)](https://packagist.org/packages/flipbox/craft-psr3)

This package provides simple mechanism for PSR-3 logging via Craft CMS.

## Installation

To install, use composer:

```
composer require flipboxdigital/craft-psr3
```

## Testing

``` bash
$ ./vendor/bin/phpunit
```

## Usage
Define it as a component in your plugin
```php 
'components' => [
    'psr3logger' => [
        'class' => flipbox\craft\psr3\Logger::class
     ]
]
```
or via your composer as an 'extra' definition
```json
"components": {
  "psr3logger": "flipbox\\craft\\psr3\\Logger"
}
```

## Contributing

Please see [CONTRIBUTING](https://github.com/flipbox/craft-psr3/blob/master/CONTRIBUTING.md) for details.


## Credits

- [Flipbox Digital](https://github.com/flipbox)

## License

The MIT License (MIT). Please see [License File](https://github.com/flipbox/craft-psr3/blob/master/LICENSE) for more information.
