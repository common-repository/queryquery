=== Query Query Wordpress Query ===

Author: Zachary A. Martz
Contributors: zamartz
Donate link: http://bt.zamartz.com/RpKg9V
Tags: wp_query,query,zamartz,shortcode
Requires at least: 3.0.1
Tested up to: 4.7.1
Stable Tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

Wordpress wp_query plugin - Ability to make WP Queries within Posts and Pages through shortcode. It can also be used to create "related" post content. It comes in a variety of view options and allows for Admin Defaults as well as shortcode overrides.

== Installation ==

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Customaize default settings thought admin via "QueryQuery" menue link
1. Instert [QueryQuery] into any page/post content you want default posts to appear.

== Frequently Asked Questions ==

= How do the queries work? =

All queries are base off of the WP_Query loop. This makes the call easy to access via a short code with overrieds.

All calls match up directly with what the name is in the WP documentation and Variable names are listed in the QueryQuery Defaults section. 

[WP_Query Documentation](https://codex.wordpress.org/Class_Reference/WP_Query)


== Screenshots ==

1. [QueryQuery] - This does the standard format that is shown when the basic shortcode is used. If there is no featured image applied to show a thumbnail a default thumbnail is applied. `/assets/standard.png`
2. [QueryQuery disablethumbnails="1"] - This is the standard view with the featured images disabled. This will disable both applied and fallback thumbnail imaged. `/assets/standard-no-image.png`
3. [QueryQuery disablethumbnails="1" disabledate="1"] - This is the standard view with no image and no date shown. `/assets/standard-no-image-date.png`
4. [QueryQuery disablethumbnails="1" disabledate="1" disableexcerpt="1" ] - This is the standard view with no image, no date shown, and no excerpt. `/assets/standard-no-image-date-exerpt.png`
5. All &#091;QueryQuery&#093; shortcodes have defaults set on install. Those defaults can be seen in the last column within the table under the &quot;Default&quot; tab. Each of these Default values can be overridden with corrisponding admin values. These defaults or override values function as &quot;Global&quot; when using &#091;QueryQuery&#093; shortcode. Any shortcode variables you place within a &#091;QueryQuery&#093; shortcode override admin values for that specific instance of the &#091;QueryQuery&#093; shortcode tag. Avalible shortcode values for &#091;QueryQuery&#093; shortcode are listed with the correct spelling on this same &quot;Default&quot; tab page. `/assets/admin-default.png`
6. This is a helper page to explain the plugin and use once you have installed the plugin. `/assets/admin-example.png`

== Changelog ==

[QueryQuery GitRepo](https://github.com/zamartz/QueryQuery)

= 1.0 =

* Original Upload

= 1.2.0 =

* Tested on WP 4.0
* Added Post_Types to selection and override

== Upgrade Notice ==

1.2.0 Teste in current wordpress version and added functionality of post_types