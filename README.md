# Youshido Symfony2 PHP CodeSniffer Coding Standard

This standard copy [Symfony2](https://github.com/djoos/Symfony2-coding-standard) one with following changes:
- Concatenation spacing equal 1

### Installation

This standard can be installed with the [Composer](https://getcomposer.org/) dependency manager.

Install the coding standard as a dependency of your project

        composer require --dev youshido/cs-code-standard

### Usage

Run CodeSniffer with following parameters to check your project code style:

        ./vendor/bin/phpcs --encoding=utf-8 --extensions=php --standard=./vendor/youshido/cs-code-standard ./src -p
