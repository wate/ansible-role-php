php
=================

Setup php

OS Platform
-----------------

### Debian

- bullseye
- buster

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `php_version`

インストールするバージョン  
対応バージョン：5.6 / 7.0 / 7.1 / 7.2 / 7.3 / 7.4 / 8.0 / 8.1 / **8.2**  
初期値：8.2

### `php_packages`

インストールするパッケージ

### `php_cfg`

PHPの設定(ベース)

### `php_cli_cfg`

PHPの設定(cli)

### `php_fpm_cfg`

PHPの設定(php-fpm)

### `php_apache_cfg`

PHPの設定(apache)

### `php_composer_version`

インストールするcomposerのバージョン

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: php
```

License
--------------

Apache License 2.0
