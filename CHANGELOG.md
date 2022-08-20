# Changelog

## [Unreleased]

## [2018-04-22a~ynhXX]

### Added

- Upgrade actions and config-panel scripts

------------

# [2022.07.31~ynh1] - 2022-08-XX

## Added

- New DokuWiki version `2022-07-31 "Igor"`
- New automated tests for "check_process" CI

## Changed

- Use PHP8.1 as default (PHP7.4 is bulleyes will be EOL "28 Nov 2022" so bump the version)
- Change method to "automatic upgrade" of plugins
- Cleanning 'admin permission' handling
- redo how php is managed: ynh_add_fpm_config + php config files
- Sync with reference package 'example_ynh'

## Removed

- automatic installation of plugin "logautherror" (not compatible)
- support for YunoHost below 11 (no time to test against older versions)

# [2020-07-29~ynh4] - 2021-01-19

### Added

- Support for new permission system in YunoHost 3.7

### Changed

- wiki administrators is now a group and can be modified from webadmin YunoHost panel
- Require YunoHost 3.7 minimum

## [2020-07-29~ynh2] - 2020-10-23

### Added

- New DokuWiki version `2020-07-29`

### Changed

- Set PHP7.3 as default

## [2018-04-22b~ynh1] - 2020-03-23

### Added

- New DokuWiki version `2018-04-22b`
- Changelog available in `CHANGELOG.md`

### Changed

- Upgrade content of file `pull_request_template.md`

## [2018-04-22a~ynh3] - 2020-02-20

### Added

- Use 'URL rewrite' for prettier URLs

### Changed

- Activate URL rewrite by default (does not break old links)

### Removed

- Unused DokuWiki config file

## [2018-04-22a~ynh2] - 2020-02-20

### Added

- Add fail2ban support to avoid bruteforce login attempts

### Changed

- Global upgrade of the package

### Fixed

- Get rid of the php ini file and merge its content into the pool file
- Update Readme following last work made on the package and current version in testing branch

### Removed

- Unused config file settings

## [Previous versions] - YYYY-MM-DD

- Will be written (one day maybye)
