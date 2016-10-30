# WordPress Dropin & Plugin Collection: Safe Fast & Clean
This is plugin and dropin collection which is intended as an alias to multiple other plugins.

## Guidelines
### WordPress should expose as little as possible about itself and plugins
* All unneccessary html comments and headers should be stripped away.

### WordPress shouldn't make any additional requests to wordpress.org or 3rd party services
* WordPress should disable anything related to updates of core/themes/plugins.
* WordPress shouldn't create unneccessary requests which either slow the page down or use cpu cycles without any additional value

### Cache as much as possible
* Caching reduces load and allows us to create faster sites

### Avoid situations where users can accidentally create errors
WordPress core development moves a bit slower with some enhancements. We will add plugins that provide fixes for problems like accented file uploads into this collection. Once those features or fixes are not needed anymore we will disable them from this package.

### Allow developers to define as much settings as possible in wp-config.php
Too many plugins have only wp-admin settings pages. We believe that most of the settings belong into code rather than the database.

## Requirements
* >= PHP 7.0
* WordPress
* Redis server for object caching
* Use composer to update your site rather than using WordPress auto updates

## License
Respect the licenses of used libraries.
