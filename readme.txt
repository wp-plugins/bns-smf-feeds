=== BNS Featured Category ===
Contributors: cais
Donate link: http://buynowshop.com
Tags: RSS, SMF, Multiple Widgets, Option Panel
Requires at least: 2.8
Tested up to: 2.9
Stable tag: 1.0

Plugin with multi-widget functionality that builds an SMF Forum RSS2 feed url by user option choices; and, displays a SMF forum feed.

== Description ==

Plugin with multi-widget functionality that builds an SMF Forum RSS2 feed url by user option choices; and, displays a SMF forum feed. The widget includes the additional option to include in the feed: specific boards and/or specific categories. There are also check boxes to include the feed item date, summary, and author. Please note, the author option is not currently supported in a standard SMF forum feed, but is included for future possibilities.

== Installation ==

This section describes how to install the plugin and get it working.

1. Upload `bns-smf-feeds.php` to the `/wp-content/plugins/` directory
2. Activate through the 'Plugins' menu.
3. Place the BNS SMF Feeds widget appropriately in the Appearance | Widgets section of the dashboard.
4. Set options to personal preferences:
* Widget Title
* Specify the full URL to the SMF Forum (e.g.: http://www.simplemachines.org/community/)
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

= 1.0 =
* Initial Release.