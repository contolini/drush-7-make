Drupal 7 makefiles and installation profiles
============

Some drush makefiles and installation profiles that I regularly use for Drupal 7

## Usage

* Clone or download files.
* Have drush download drupal and requested modules: `drush make d7-omega.make DRUPAL-ROOT` where DRUPAL-ROOT is the directory in which you want Drupal to reside.
* Copy the profile you want to use to the site's root: `cp -r profiles/foundation DRUPAL-ROOT/profiles`
* Start up your webserver, visit the site in your browser, and select the above installation profile when installing Drupal.