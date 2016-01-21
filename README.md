# m2-koncz-hello

### Installation

```sh
$ composer config repositories.koncz-m2-koncz-hello git git@github.com:ksz2013/m2-koncz-hello.git
$ composer require koncz/m2-koncz-hello:dev-master
```

Manually:

Copy the zip into app/code/Koncz/Hello directory


#### After installation by either means, enable the extension by running following commands:

```sh
$ php bin/magento module:enable Koncz_Hello --clear-static-content
$ php bin/magento setup:upgrade
```