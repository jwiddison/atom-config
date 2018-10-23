# Atom Config Backup

`config.cson` can be copied over top of a clean install's config file to restore editor settings.

`packages.list` is created using the following command:

```
apm list --installed --bare > packages.list
```

The packages can be pulled and installed from this file using:

```
apm install `cat packages.list`
```
