# php-qr-code
PHP QR Code Generator compatible with PHP 7.0
Ported from [http://phpqrcode.sourceforge.net/](http://phpqrcode.sourceforge.net/)

## Installation
The recommended method of installing this library is via [Composer](https://getcomposer.org/).

Run the following command from your project root:

```bash
$ composer require drbiko/php-qr-code
```

## Usage 
```php
require __DIR__ . "/vendor/autoload.php";
QRcode::png('https://github.com/drbiko/php-qr-code', false, QR_ECLEVEL_H, 10, 0);
```

[examples] (http://phpqrcode.sourceforge.net/examples/index.php)

## Acknowledgements

This library is an import of PHP QR Code by Dominik Dzienia that you can find at http://phpqrcode.sourceforge.net

Based on C libqrencode library (ver. 3.1.1), Copyright (C) 2006-2010 by Kentaro Fukuchi
http://megaui.net/fukuchi/works/qrencode/index.en.html

QR Code is registered trademarks of DENSO WAVE INCORPORATED in JAPAN and other countries.

Reed-Solomon code encoder is written by Phil Karn, KA9Q. Copyright (C) 2002, 2003, 2004, 2006 Phil Karn, KA9Q