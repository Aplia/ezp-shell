# eZ Legacy Shell

This an integration of PsySh and the eZ publish legacy kernel.
It initializes the kernel and starts a new PsySh.

The shell has some additional variables related to eZ publish:
- `kernel` - The current kernel instance.
- `user` - The currently logged in user, usually admin.
- `db` - The current db instance.
- `site_ini` - The INI instance for `site.ini`.

Also if the Starter-Bootstrap is available it also makes these variables available:
- `app` - The base application instance.
- `config` - The base configuration instance.
