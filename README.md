# AG Element distribution

This repository is the update channel for AG Element, a WordPress plugin that
gives AI agents a REST API to read, validate and edit Elementor pages. It holds
two things: `update.json`, which installed sites poll for the current version,
and the release zips attached to the releases here.

The plugin source is not here. This repository exists because a site's update
checker has to reach the manifest and the zip without credentials.

## Installing

```bash
wp plugin install https://github.com/alex-elivate/ag-element-dist/releases/latest/download/ag-element.zip --activate
```

Sites that already have the plugin update themselves from `update.json`, and
show the update in the Plugins screen like any other.

## License

GPL-3.0-or-later. The zip contains the plugin's complete source, which for a
PHP plugin is the same thing as the distribution.
