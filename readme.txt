=== LittleSis Blog Project ===
Contributors: misfist
Requires at least: 4.7
Tested up to: 4.7.2
License: GPLv3

WordPress packages for blog.littlesis.org

== Description ==
Package configuration for WordPress plugins and themes used on blog.littlesis.org.

== Installation ==
The `composer.json` file contains the packages used by the site.

Run `composer install` (or `composer install --no-dev`) within the package directory in order to install for the first time.
Run `composer update` (or `composer update --no-dev`)  within the package directory in order to update the project.

Important: When installing or updating on a production environment, use the `--no-dev` flag so that packages used for development are not included.

Project structure

```
webroot
 \\_ core-packages <-- contains composer.json - installs packages into wordpress direcgtory
  \\_ wordpress <-- contains wordpress core and packages
```

== Changelog ==

0.0.1 - Initial