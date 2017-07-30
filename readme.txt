=== mPress Hide from Search ===
Contributors: woodent
Donate link: https://www.paypal.me/wpscholar
Tags: search, WordPress search, hide from search, exclude from search, hide post, hidden posts, thank you pages
Requires at least: 3.2
Tested up to: 4.8
Stable tag: 1.0.0
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Hide individual public pages from WordPress search, such as confirmation and download pages that should only be accessible via a squeeze page.

== Description ==

The **mPress Hide from Search** plugin allows to you hide specific pages from WordPress search.

= Why? =

It isn't uncommon to have pages on your site that are public, but not intended to be found. Take, for example, a download page where people who have signed up for your email newsletter can download your amazing white paper.  You don't want just anyone to be able to download your white paper, but the page has to be public because people who sign up for your newsletter aren't going to be logged into your site.  You were smart enough to use your favorite SEO plugin and block the search engines from indexing that page, but now you have realized that people who perform a search on your site for the title of the white paper are taken directly to the download page.  The solution?  Download this plugin and hide your download page from WordPress search!

= How? =

Using this plugin is simple:

1. Install the plugin
2. Activate the plugin
3. Go to a post you want to hide and check the 'Hide from search' checkbox on the bottom right of the screen.
4. Save your changes

= Features =

* Works with custom post types
* No settings page, just a simple, easy-to-use checkbox
* Clean, well written code that won't bog down your site

== Installation ==

= Prerequisites =
If you don't meet the below requirements, I highly recommend you upgrade your WordPress install or move to a web host that supports a more recent version of PHP.

* Requires WordPress version 3.2 or greater
* Requires PHP version 5.2.4 or greater ( PHP version 5.2.4 is required to run WordPress version 3.2 )

= The Easy Way =

1. In your WordPress admin, go to 'Plugins' and then click on 'Add New'.
2. In the search box, type in 'mPress Hide from Search' and hit enter.  This plugin should be the first and likely the only result.
3. Click on the 'Install' link.
4. Once installed, click the 'Activate this plugin' link.

= The Hard Way =

1. Download the .zip file containing the plugin.
2. Upload the file into your `/wp-content/plugins/` directory and unzip
3. Find the plugin in the WordPress admin on the 'Plugins' page and click 'Activate'

= Usage Instructions =

Once the plugin is installed and activated, go to a post you want to hide and check the 'Hide from search' checkbox on
the bottom right of the screen and save your changes.  Viola! The post has been hidden!

== Screenshots ==

1. Using the plugin is simple, just check the box to hide a page or post.

== Changelog ==

= 1.0.0 =
* Tested in WordPress version 4.7
* Escaped translated strings, for security.
* Converted singleton to static class.
* Updated .pot translation file to include additional plugin information.

= 0.4.3 =
* Tested in WordPress version 4.5.2

= 0.4.2 =
* Tested in WordPress version 4.4.3

= 0.4.1 =
* Tested in WordPress version 4.2.4

= 0.4 =
* Tested in WordPress version 4.0
* Added additional comments to the code
* Tweaked how translations are loaded.

= 0.3 =
* Tested in WordPress version 3.5.1
* Deleted MPRESS_HIDE_FROM_SEARCH_VERSION constant and created a public static variable instead
* Fire class on plugins_loaded action instead of on load.
* Added call to load_plugin_textdomain()

= 0.2 =
* Added MPRESS_HIDE_FROM_SEARCH_VERSION constant
* Made class a true singleton

= 0.1 =
* Initial commit

== Upgrade Notice ==

= 1.0.0 =
Plugin updated to reflect that it words with WordPress version 4.7. Escaped translated strings for security.

= 0.4.3 =
Plugin updated to reflect that it works with WordPress version 4.5.2

= 0.4.1 =
Plugin updated to reflect that it works with WordPress version 4.2.4

= 0.4 =
Updated plugin structure and how translations are loaded.

= 0.3 =
Made plugin fully translatable and made some minor tweaks to the code.

= 0.2 =
Minor code improvements