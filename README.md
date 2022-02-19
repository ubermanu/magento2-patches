# Magento 2 Patches

A collection of patches for Magento 2.

## Usage

Install [cweagans/composer-patches](https://github.com/cweagans/composer-patches) in your project.

    composer require cweagans/composer-patches

Add the patches you need to your `composer.json`:

```json
{
  "extra": {
    "patches": {
      "magento/magento2-functional-testing-framework": [
        "https://ubermanu.github.io/magento2-patches/magento/magento2-functional-testing-framework/fix_xdebug_disable.patch"
      ]
    }
  }
}
```

## Patches

#### fix_xdebug_disable.patch

Fixed in version 3.2.1 of `magento/magento2-functional-testing-framework`.

- https://magento.stackexchange.com/q/327971/101630
- https://github.com/magento/magento2/issues/28961#issuecomment-759269458
