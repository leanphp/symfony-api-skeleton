symfony-skeleton
================

[symfony-skeleton][0] is a minimal symfony project skeleton for web
applications. It provides minimal set of symfony bundles for development. It is
based on [symfony/skeleton][1].

## Bundles

- `doctrine/mongodb-odm-bundle`
- `incenteev/composer-parameter-handler`
- `jms/serializer-bundle`
- `sensio/framework-extra-bundle`
- `symfony/monolog-bundle`
- `symfony/orm-pack` (Doctrine)
- `symfony/profiler-pack`
- `symfony/psr-http-message-bridge`
- `zendframework/zend-diactoros`

A list of development bundles (`require-dev`):

- `doctrine/doctrine-fixtures-bndle`
- `symfony/maker-bundle`
- `symfony/web-server-bundle`

## Install

```bash
composer create-project leanphp/symfony-skeleton my-project-name
```

## Authors

Copyright (c) 2018 ek9 <dev@ek9.co> (https://ek9.co).

## License

Licensed under [MIT License](./LICENSE)

[0]: https://github.com/leanphp/symfony-skeleton
[1]: https://github.com/symfony/skeleton
