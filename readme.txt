=== BNS SMF Feeds ===
Contributors: cais
Donate link: http://buynowshop.com
Tags: RSS, SMF, Multiple Widgets, Option Panel
Requires at least: 2.8
Tested up to: 2.9.1
Stable tag: 1.3.1

Plugin with multi-widget functionality that builds an SMF Forum RSS feed url by user option choices; and, displays a SMF forum feed.

== Description ==

Plugin with multi-widget functionality that builds an SMF Forum RSS feed url by user option choices; and, displays a SMF forum feed. The widget includes the additional option to include in the feed: specific boards and/or specific categories. There are also check boxes to include the feed item date and the item summary, too.

NB: If updating from a version before 1.1 please make sure to re-save your widget options (check your feed type) for each instance after upgrading. This will set the feed type correctly using the new feed drop-down selection option. Thanks! ~cais

== Installation ==

This section describes how to install the plugin and get it working.

1. Upload `bns-smf-feeds.php` to the `/wp-content/plugins/` directory
2. Activate through the 'Plugins' menu.
3. Place the BNS SMF Feeds widget appropriately in the Appearance | Widgets section of the dashboard.
4. Set options to personal preferences:

* Widget Title
* Specify the full URL to the SMF Forum (e.g.: http://www.simplemachines.org/community/)
* Choose feed type from drop-down menu (RSS, RSS2, Atom, RDF)
* The default is by recent Topics, or choose to display recent posts
* The default displays all items able to be seen by a "guest".
* Choose specific boards (or categories of boards) to include only.
* Choose the maximum quantity of items to display (varies by SMF user permissions)
* Choose to display the item date and/or item summary

-- or -

1. Go to 'Plugins' menu under your Dashboard
2. Click on the 'Add New' link
3. Search for BNS SMF Feeds
4. Install.
5. Activate through the 'Plugins' menu.
6. Place the BNS SMF Feeds widget appropriately in the Appearance | Widgets section of the dashboard.
7. Set options to personal preferences:

* Widget Title
* Specify the full URL to the SMF Forum (e.g.: http://www.simplemachines.org/community/)
* Choose feed type from drop-down menu (RSS, RSS2, Atom, RDF)
* The default is by recent Topics, or choose to display recent posts
* The default displays all items able to be seen by a "guest".
* Choose specific boards (or categories of boards) to include only.
* Choose the maximum quantity of items to display (varies by SMF user permissions)
* Choose to display the item date and/or item summary

== Frequently Asked Questions ==

= Can I use this in more than one widget area? =
Yes, this plugin has been made for multi-widget compatibility. Each instance of the widget will display, if wanted, differently than every other instance of the widget.

= How can I style the plugin output? =
The plugin uses a variation of the WordPress RSS Output that assigns several rss related classes, such as: rssSummary, rss-date, and rsswidget. A wrapping class of 'bns-smf-feeds' has also been added to the widget for more fine tuning.

= How can I get the RSS feed url? =
Once the widget is activated and placed into a widget ready area, there will be a standard RSS icon displayed beside the feed title. This icon will have the url anchored to it, simply click on it to subscribe to the feed directly.

== Screenshots ==

1. The options panel.

== Changelog ==
= 1.3.1 =
* tied all links in the widget to use the "option to open links in new window"

= 1.3 =
* removed unnecessary (commented out) code
* added option to open links in new window as suggested
* added new screenshot of option panel

= 1.2 =
* added feed refresh frequency (in seconds) option
* added new screenshot of option panel

= 1.1.1 =
* compatibility check for 2.9.1 completed

= 1.1 =
* added drop-down menu to option panel to choose feed type, default set to RSS2
* updated the Option Panel screen shot

= 1.0.1 =
* minor corrections to description and screenshot

= 1.0 =
* Initial Release.

== Upgrade Notice ==
v1.3 adds an option to control if feeds links open in a new window.