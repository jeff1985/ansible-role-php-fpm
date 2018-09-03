# ansible-php-fpm

An Ansible role for installing the PHP FastCGI process manager (FPM).

## Role Variables

- `php_fpm_version` - PHP-FPM version
- `php_fpm_upload_max_filesize` - Maximum allowed size for uploaded files
- `php_fpm_post_max_size` - Maximum size of POST data that PHP will accept
- `php_fpm_env` - Mapping of environmental variables made available to the PHP runtime

## Example Playbook

See the [examples](./examples/) directory.
