# Symfony Empty Edition

The same as [Symfony Standard Edition](https://github.com/symfony/symfony-standard),
only lighter and ready to be used (no removal/customization steps required).

## Installation

To create a new Symfony application using this distribution, get a copy of
[Composer](http://getcomposer.org/) and use its `create-project` command:

    curl -sS https://getcomposer.org/installer | php
    ./composer.phar create-project gnugat/symfony-framework-empty-edition path/to/install

Then you just need to:

1. replace `README.md` and `LICENSE`
2. start coding!

**Note**: you could bootstrap your project's markdown files (`README.md`,
`LICENSE`, `doc/02-installation.md`, etc) using [fossil](https://github.com/gnugat/fossil):

    curl -sS https://raw.github.com/gnugat/fossil/master/bin/installer.sh | sh
    fossil doc -f 'github/repo' 'Owner name for copyright'

## Differences with the standard edition

- no AcmeDemoBundle
- no Swiftmailer
- no twig-extension
- no Symfony requirement/configuration scripts
- no extra code/configuration comments
- no cache kernel
- no firephp monolog handler
- no chromephp monolog handler
- no Symfony markdown files (except `LICENSE` and `README.md`)
* empty (blank) favicons
* using PHP 5.3.17+
* vendor binaries in `vendor/bin` instead of `bin`
* uniformized syntax in configuration
+ enabled translator fallback

## Further documentation

[Copyright and MIT license](LICENSE).
