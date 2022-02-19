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
