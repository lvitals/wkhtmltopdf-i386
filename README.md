wkhtmltopdf
================

This binaries compile from source code [wkhtmltopdf project](https://github.com/wkhtmltopdf/wkhtmltopdf).
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

## Installation

_Hint_:
The version of the binary is equal to the git tag.
To install the latest version, use '0.12.3'.

In case this package does _not_ work on your system, try installing the matching system packages from here: [http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html).

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package for _amd64_ with:

    php composer.phar require lvitals/wkhtmltopdf-amd64 "0.1.2.3"

And for _i386_ with:

    php composer.phar require lvitals/wkhtmltopdf-i386 "0.1.2.3"

The binary will then be located at:

    vendor/lvitals/wkhtmltopdf-i386/bin/wkhtmltopdf-i386

Also a symlink will be created in your configured bin/ folder, for example:

    vendor/bin/wkhtmltopdf-i386
