# LightPHP Core

LightPHP Core is a framework-independent PHP 8.5 application foundation maintained by CodeverseIndia. It provides application bootstrap, request and response handling, explicit routing, template resolution, configuration, file caching, security primitives, HTTP transport, and the Spark CLI.

## Installation

Install the package with Composer:

```sh
composer require codeverseindia/lightphp-core
```

The package uses PSR-4 autoloading under `CodeverseIndia\LightPHP\`.

```php
use CodeverseIndia\LightPHP\Application;
```

## Development

From the repository root, install dependencies and run the test suite:

```sh
composer install
php tests/run.php
```

## Releases

This package is distributed through Composer. Tag releases with semantic versions, for example `v1.0.0`; Composer package versions come from Git tags rather than a `version` field in `composer.json`.
