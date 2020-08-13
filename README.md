# drupaldo

## Prerequisites

- [composer](https://getcomposer.org/)

## Installation

1. Install dependencies with composer:
    ```
    $ composer install
    ```

2. Create `/web/sites/default/settings.local.php`, and add database settings.

3. Install the site from config with:

    ```
    $ ./vendor/bin/drush site:install --existing-config
    ```

4. Create a test user, and login:

    ```
    $ ./vendor/bin/drush user:create test
    $ ./vendor/bin/drush user:login --name=test
    ```

## Demo
![Watch the video](docs/drupaldo-demo.gif)
