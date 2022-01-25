=== Plugin Name ===
Contributors: versusbassz
Tags: sortable, id, column, admin, panel
Requires at least: 4.9
Tested up to: 5.9
Stable tag: 2.1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Sortable ID columns for all standard data types in WordPress admin panel.

== Description ==

Minimalistic fork of "Reveal IDs" plugin.

ID columns will be first in admin panel tables.

= Differences from "Reveal IDs" plugin =

This plugin contains only functionality for id colums creation (i.e. the options page in the admin panel and some backward compatibility code were removed).

"Reveal IDs" code was pretty much rewritten. But the basic functionality remains the same. ID columns will be first in admin panel tables.

= Links =
<a href="https://github.com/versusbassz/sortable-id-columns/" target="_blank">Github repo</a>

= Plugins with same functionality =

* <a href="http://wordpress.org/extend/plugins/reveal-ids-for-wp-admin-25/">Reveal IDs</a> &mdash; HH sortable ID columns is fork of this plugin.
* <a href="http://wordpress.org/extend/plugins/codepress-admin-columns/">Codepress Admin Columns</a> &mdash; Complex solution to manage custom columns in admin panel ( not only ID ).
* <a href="http://wordpress.org/extend/plugins/wp-show-ids/">WP Show IDs ( simple, yet elegant )</a> &mdash; Not updated since 2011, but reviews says that it works.

== Changelog ==

= 2.1.0 --- 2021.07.07 =
* Increase width of the "ID" column: 50px -> 65px , so now it can display 6 chars without a line break (#1)
* Add the link to the Github repository of the plugin to readme.txt
* Change "Tested up to" header: 5.5 -> 5.7
* Update "Requires PHP" header: 5.3 -> 5.6
* Update "Plugin URI" and "Author URI" links in the entry PHP file

= 2.0.3 --- 2020.11.21 =
* Checked compatibility with WordPress <= 5.5

= 2.0.2 --- 2017.03.16 =
* Fix PHP 5.3 compatibility

= 2.0.1 --- 2017.02.24 =
* Fix plugin meta and "Changelog" tab in readme.txt

= 2.0.0 --- 2017.02.24 =
* Code style changes
* Change "Tested up to" meta-field to "4.7.2"
* Change "Requires at least" meta-field to "4.6"
* Change "Plugin URI" meta-field
* Change "Author URI" meta-field
* Remove unnecessary code
* Change column insert algorithm
* Add "Differences from "Reveal IDs" plugin" section in readme.txt
* Add "Plugins with same functionality" section in readme.txt

= 1.0.0 --- 2013.04.30 =
* Initial release.
