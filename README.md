# Symfony Empty Edition

The Symfony Empty Edition is a light distribution of the
[Symfony Standard Edition](https://github.com/symfony/symfony-standard)
that you can use as a skeleton ready to use for your Symfony projects.

## Installation

To create a new Symfony application using this distribution, get a copy of
[Composer](http://getcomposer.org/) and  use its `create-project` command:

    curl -sS https://getcomposer.org/installer | php
    ./composer.phar create-project gnugat/symfony-framework-empty-edition path/to/install

## Differences with the standard edition

* no AcmeDemonBundle;
* empty (blank) favicons;
* using twig without extensions;
* using PHP 5.3.17+;
* not using Swiftmailer;
* no requirement tests;
* intercepting redirection in dev environment.

## Further documentation

You can find more documentation at the following links:

* [Copyright and MIT license](LICENSE.md);
* [contribution instructions](CONTRIBUTING.md).
