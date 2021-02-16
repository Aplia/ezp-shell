# eZ Legacy Shell

This an integration of PsySh and the eZ publish legacy kernel.
It initializes the kernel and starts a new PsySh.

[![Latest Stable Version](https://img.shields.io/packagist/v/aplia/ez-legacy-shell.svg?style=flat-square)](https://packagist.org/packages/aplia/ez-legacy-shell)
[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%205.3-8892BF.svg?style=flat-square)](https://php.net/)

This is similar to the `ezsh` project https://github.com/lolautruche/ezsh,
but does not require the new eZ publish stack.

The shell has some additional variables related to eZ publish:

- `kernel` - The current kernel instance.
- `user` - The currently logged in user, usually admin.
- `db` - The current db instance.
- `site_ini` - The INI instance for `site.ini`.

Also if the Starter-Bootstrap is available it also makes these variables available:

- `app` - The base application instance.
- `config` - The base configuration instance.

## Installation

```shell
composer require aplia/ez-legacy-shell:@stable
```

## Usage

Start the shell from the vendor bin folder.

```shell
vendor/bin/ezpsh
```
