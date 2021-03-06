<div align="center">
  <h1>
    <br/>
    <div>⚙</div>
   
Laravel Config Maker

  </h1>
  <sup>

[![Latest Version on Packagist](https://img.shields.io/packagist/v/gabrielfemi/laravel-config-maker.svg?style=flat-square)](https://packagist.org/packages/gabrielfemi/laravel-config-maker)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/gabrielfemi/laravel-config-maker/run-tests?label=tests)](https://github.com/gabrielfemi/laravel-config-maker/actions?query=workflow%3Arun-tests+branch%3Amaster)
[![Total Downloads](https://img.shields.io/packagist/dt/gabrielfemi/laravel-config-maker.svg?style=flat-square)](https://packagist.org/packages/gabrielfemi/laravel-config-maker)


Quickly create your configuration files.
=======
<br /> 
</sup>
<br />

  <pre>composer require <a href="https://packagist.org/packages/gabrielfemi/laravel-config-maker">gabrielfemi/laravel-config-maker</a></pre>
  <br />
</div>

## Usage
<pre>php artisan <a href="#">config:make</a> test</pre>

This creates a file in the ```config``` directory called ```test.php```

The default content of the file is 
```php
return [
];
``` 
## Testing

``` bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Gabriel Akinyosoye](https://github.com/GabrielFemi)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
