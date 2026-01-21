php
=================

Setup php

OS Platform
-----------------

### Debian

- trixie
- bookworm

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `php_version`

インストールするバージョン  
対応バージョン：7.4 / 8.0 / 8.1 / 8.2 / 8.3 / 8.4 / **8.5**  
初期値：8.5

#### `php_packages`

インストールするパッケージ

#### `php_cfg`

PHPの設定(ベース)

#### `php_cli_cfg`

PHPの設定(cli)

#### `php_fpm_cfg`

PHPの設定(php-fpm)

#### `php_apache_cfg`

PHPの設定(apache)

#### `php_composer_version`

インストールするcomposerのバージョン

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `php_apt_key_url`

#### `php_apt_key_dest`

#### `php_conf_dir`

#### `php_cli_conf_dir`

#### `php_fpm_conf_dir`

#### `php_apache_conf_dir`

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
