# Patches

### fix_xdebug_disable

Avoid an error when xdebug is enabled in a DDEV environment.

- https://magento.stackexchange.com/q/327971/101630
- https://github.com/magento/magento2/issues/28961#issuecomment-759269458

### add_integration_cleanup_database

Avoid `setup:install` errors when running integration tests on an existing database.

- https://magento.stackexchange.com/q/167138/101630
