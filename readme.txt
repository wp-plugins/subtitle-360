=== Plugin Name ===
Contributors: HasanulBanna
Tags: page title, subtitle, page sub title
Requires at least: 3.0
Tested up to: 3.3.1
Stable tag: 1.0

This plugin creates a option to enter sub heading for pages and posts. You can display the sub title in your theme by using the <code><?php if (function_exists('the_subtitle')){ the_subtitle(); }?></code> template tag.

== Description ==

This plugin creates a option to enter sub heading for pages and posts. You can display the sub title in your theme by using the <code><?php if (function_exists('the_subtitle')){ the_subtitle(); }?></code> template tag.

== Installation ==

1. Upload the entire `subtitle-360` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Now under pages and posts you can see option to enter sub title.

== Frequently Asked Questions ==

= My Sub title won't upload. What should I do? =

You may be forgot to add template code to the area you want to display subtitle.
<code><?php if (function_exists('the_subtitle')){ the_subtitle(); }?></code>

== Changelog ==

= 1.0 =
* Initial Release