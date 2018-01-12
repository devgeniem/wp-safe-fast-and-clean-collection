# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2018-01-12

### Removed

- Removed `devgeniem/wp-polylang-remove-ads`. This fix is no longer needed.

## [1.1.0] - 2017-12-13

### Added

- Added `devgeniem/wp-polylang-remove-ads` to remove ads from free version of Polylang.

## [1.0.2]

### Added

* Added `devgeniem/wp-core-fixes` to fix rss feeds in WordPress 4.7.

## [1.0.1]

### Added

* Added `roots/wp-password-bcrypt` to make change default password hash to stronger one ( md5 -> brcypt ).

## [1.0]

### Added

* Added `aucor/dynamic-mo-loader` because it makes our sites load faster.
* Added `devgeniem/better-wp-install-dropin` so that cleanly installed WordPress wouldn't contain as much bloat.
* Added `devgeniem/wp-core-blocker` to disable all WordPress core updates.
* Added `devgeniem/wp-define-more` so that we can have more variables to define in `wp-config.php`.
* Added `devgeniem/wp-readonly-options` to force plugin options in our `wp-config.php`.
* Added `devgeniem/wp-sanitize-accented-uploads` so that accented file uploads won't during the migrations.
* Added `devgeniem/wp-no-admin-ajax` to change `/wp-admin/admin-ajax.php` endpoint automatically to pretty url.

