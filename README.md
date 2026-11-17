# WP URL Shorten

Shortens URLs of your blog posts via eeb.me, zpit.us, cvrd.us and eaby.us. WordPress.org plugin: https://wordpress.org/plugins/wp-url-shorten/

## Deployment

- Push to `main`: SVN `trunk` is updated.
- Push a version tag (e.g. `10.2`): SVN `trunk` and `tags/<version>` are created. The tag must equal the `Version:` header in `eebme_shorturl.php` and `Stable tag` in `readme.txt`.
- Changes in `.wordpress-org/`: SVN `assets` are updated.
