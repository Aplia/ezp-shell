# eZ Legacy Shell

This an integration of PsySh and the eZ publish legacy kernel.
It initializes the kernel and starts a new PsySh.

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
