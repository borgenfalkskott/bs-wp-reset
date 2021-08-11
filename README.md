# bs-wp-reset

A reset plugin to make WordPress tight.

## What does this mu-plugin do?

### Disabling:

- File editing
- Wp version in meta
- XML-RPC
- RSS meta
- Admin bar
- jQuery
- Wp Emojis

### Login page

- Wp logo links to start page
- Wp logo alt text
- Login error message is more secure

## Install

### Composer

```
composer require borgenfalkskott/bs-wp-reset
```

### Bedrock

Simply add it to `app/mu-plugins/` to have [Bedrock](https://roots.io/bedrock/) autoload it.

### Vanilla WordPress

If you are not using Bedrock, simply add an autoloader file in `wp-content/mu-plugins/` like this, to have WordPress run this plugin:

```php
// autoloader.php:

<?php
  /**
   * WordPress Mu Plugin Autoloader
   */
  require_once __DIR__ . '/bs-wp-reset/bs-wp-reset.php';
?>
```

## What is a mu-plugin?

Nowadays it stands for "must use plugin", meaning that it is activated automatically by just adding it to the `/wp-content/mu-plugins` folder.

Single file mu-plugins that sits directly inside the `mu-plugins` folder, are loaded automatically by WordPress.

For mu-plugins that live inside a subfolder, they need to be autoloaded like the example above or by using something like [Bedrock](https://roots.io/bedrock/).

Read more about mu-plugins [here](https://wordpress.org/support/article/must-use-plugins/).

## Support our work

⭐️ Star this repo on [GitHub](https://github.com/borgenfalkskott/bs-wp-reset).

⭐️ Star this package on [Packagist](https://packagist.org/packages/borgenfalkskott/bs-wp-reset).

❤️ Buy me a [coffee](https://github.com/sponsors/borgenfalkskott).
