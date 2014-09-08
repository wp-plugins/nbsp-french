=== NBSP French ===
Contributors: jsmoriss
Tags: nbsp, french, exclamation, question, interrogation, line-break
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.txt
Requires At Least: 3.0
Tested Up To: 4.0
Stable Tag: 1.4

Adds a non-breaking space between words and punctuation marks to avoid inappropriate line-breaks in French.

== Description ==

Adds a non-breaking space between words and punctuation marks to avoid inappropriate line-breaks in French. Recognized punctuation:

* !
* ?
* :
* ;
* %
* &laquo;
* &raquo;

The plugin will add non-breaking spaces where appropriate in the content, excerpt, comments, and text widget &mdash; skipping over pre-formatted code blocks and scripts &mdash; and if the `<!--:fr-->` HTML  tag is found, non-breaking spaces are only added between the `<!--:fr-->` and `<!--:-->` HTML tags.

== Installation ==

*Using the WordPress Dashboard*

1. Login to your weblog
1. Go to Plugins
1. Select Add New
1. Search for *NBSP French*
1. Select Install
1. Select Install Now
1. Select Activate Plugin

*Manual*

1. Download and unzip the plugin
1. Upload the entire `nbsp-french/` folder to the `wp-content/plugins/` directory
1. Activate the plugin through the Plugins menu in WordPress

== Frequently Asked Questions ==

== Changelog ==

= Version 1.4 =

* Bugfixes
	* *None*
* Enhancements
	* Added the NGFB French filter to 'widget_text' as well.

= Version 1.3 =

* Bugfixes
	* *None*
* Enhancements
	* Added support for the percentage character.

= Version 1.2 =

* Bugfixes
	* Fixed the detection of comment, javascript, and pre-formatted text start/end blocks.
* Enhancements
	* *None*

= Version 1.1 =

* Bugfixes
	* *None*
* Enhancements
	* Added detection of `<!--:fr-->` and `<!--:-->` to insert `&nbsp;` only between these tags.
	* Added support for the colon, semi-colon, and double angle quotation marks (props X-Raym).

== Upgrade Notice ==

= 1.4 =

Added the NGFB French filter to 'widget_text' as well.

= 1.3 =

Added support for the percentage character.

