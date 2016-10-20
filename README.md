# php-micropub

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]


Micropub is a spec to create content on a server using web or native app clients. Micropub is primarily focused around creating "posts" (individual pieces of content such as blog posts, photos, short notes, or responses) on a website, although it can be used for other kinds of content as well. ** This library is in active development and is not recommended for use **

## Install

Via Composer

``` bash
$ composer require dansup/php-micropub
```

## Usage

``` php
$skeleton = new Dansup\Micropub();
echo $skeleton->echoPhrase('Hello, League!');
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for details.

## Security

If you discover any security related issues, please email :author_email instead of using the issue tracker.

## Credits

- [Daniel Supernault][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/dansup/php-micropub.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/dansup/php-micropub/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/dansup/php-micropub.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/dansup/php-micropub.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/dansup/php-micropub.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/dansup/php-micropub
[link-travis]: https://travis-ci.org/dansup/php-micropub
[link-scrutinizer]: https://scrutinizer-ci.com/g/dansup/php-micropub/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/dansup/php-micropub
[link-downloads]: https://packagist.org/packages/dansup/php-micropub
[link-author]: https://github.com/dansup
[link-contributors]: ../../contributors
