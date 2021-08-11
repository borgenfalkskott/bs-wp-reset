# bs-wp-reset

A reset plugin to make WordPress tight.

## Install

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
