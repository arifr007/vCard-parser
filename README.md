# vCard Parser
[![Laravel 5.1](https://img.shields.io/badge/Laravel-5.1-orange.svg?style=flat-square)](http://laravel.com)
[![Build Status](https://img.shields.io/badge/build-0.1-lightgrey.svg?style=flat-square)](https://github.com/arifr007/vcard-parser)
[![Source](https://img.shields.io/badge/source-arifr007%2Fvcard--parser-blue.svg?style=flat-square)](https://github.com/arifr007/vcard-parser)
[![License](http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](https://tldrlegal.com/license/mit-license)

vCard-parser is a simple vCard file parser with the focus on ease of use.

The parser was written mostly because I couldn't find one that I was satisfied with - all those that I tried either failed with real world data or were too unwieldy or inconvenient, hence this parser.

The parser can read both single and multiple vCards from a single file and with the help of PHP's magic methods and interfaces it can be written concisely.

Documentation
-------------
You will find user friendly and updated documentation in the wiki here: [vCard Parser Wiki](https://github.com/arifr007/vcard-parser/wiki)

Quick Installation
------------------
Begin by installing the package through Composer.

```
composer require arifr007/vcard-parser
```

Once this operation is complete, simply add facade classes to your project's `config/app.php` file:

```php
'vCard' => Arifr007\vCardParser\vCard::class,
```

## Contributing

Contributions are **welcome** and will be fully **credited**.

### Issues

> For bug reporting or code discussions.

More info on how to work with GitHub on help.github.com.

### Credits
> this project's base from [Nuovo](https://github.com/nuovo/vCard-parser) vCard Parser and converting to laravel 5.1 library

## License

The module is licensed under [MIT](./LICENSE.md). In short, this license allows you to do everything as long as the copyright statement stays present.