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

### `php_version`

インストールするバージョン  
※7.0 OR 7.1 OR 7.2 OR 7.3 OR 7.4 OR 8.0 OR 8.1

### `php_packages`

インストールするパッケージ

### `php_cfg`

PHPの共通設定(全体)

### `php_cli_cfg`

PHPの共通設定(cli)

### `php_fpm_cfg`

PHPの共通設定(php-fpm)

### `php_apache_cfg`

PHPの共通設定(apache)

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
