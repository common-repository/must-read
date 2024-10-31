=== Must Read! ===
Contributors: Kubitomakita
Donate link: https://www.paypal.me/underDEV/
Tags: widget, list, post list, must read
Requires at least: 4.6
Requires PHP: 5.3
Tested up to: 4.9
Stable tag: 1.0.0

Mark your articles as a "Must Read" and display them in a widget or via shortcode or function

== Description ==

This plugin allows you to mark any of your articles as a "Must Read" to display them anywhere in a pretty convenient way.

There are three possible ways to display the list.

**Widget**

Just go to the Widgets screen and find the "Must Read!" widget. You can place it in any sidebar and adjust the settings.

**Shortcode**

`[mustread number=5 image=above_title date=1 author=1 excerpt=1]`

All supported params and their values are available in the FAQ section.

**PHP function**

`mustread( array(
	'posts_number'    => 5,     // integer
	'display_image'   => false, // false|above_title|below_title
	'display_date'    => false, // true|false
	'display_author'  => false, // true|false
	'display_excerpt' => false, // true|false
), true );`

The last parameter controls the output of the function. If you provide a `false` there, the function will return list HTML.

== Installation ==

Go to your WordPress wp-admin. Plugins -> Add New. Search for "Must Read!" and install it.

== Frequently Asked Questions ==

= Is there a post number limit on the list? =

By default, it's 5, but you can control this in the widget settings or shortcode/function parameters.

= What are the shortcode parameters? =

Supported shortcode params are:

* number  - integer - number of posts to display
* image   - 0|above_title|below_title - if display the image and where
* date    - 1|0 - if display the post date
* author  - 1|0 - if display the post author
* excerpt - 1|0 - if display the post excerpt

== Screenshots ==

1. Widget with the list
2. Must Read setting on post edit screen
3. Widget settings

== Changelog ==

= 1.0.0 =
Initial release
