=== SEO Links Generator ===
Contributors: vimal.ghorecha
Donate link: http://www.eryushion.com/wordpress-plugins/seo-links-generator/
Tags:  post, posts, pages, tags, categories, comments, links, seo, google, automatic, link
Requires at least: 2.3
Tested up to: 4.6
Requires PHP: 5.2.4
Stable tag: 1.0
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

With SEO Links Generator you can easily add links (automatically) for keywords and phrases in posts, pages and comments.

== Description == 

With SEO Links Generator you can easily add links (automatically) for keywords and phrases in posts, pages and comments and link them to corresponding posts, pages, categories, tags or any URL.

On the organized settings page in the admin area you can change settings for internal links, custom keywords, excluding and targeting.

== Changelog == 

= 1.0 =
* First release

== Credits ==

The SEO Links Generator plugin is based on the SEO Smart Links 2.7.6 by Vladimir Prelovac:

* [Vladimir Prelovac ](http://www.prelovac.com/vladimir/  "Vladimir Prelovac ") for his [SEO Smart Links](http://wordpress.org/plugins/seo-automatic-links/  "SEO Smart Links") plugin.

== Installation ==

1. Upload the complete seo-links-generator folder to your /wp-content/plugins/ folder.
2. Go to the Plugins page and activate the plugin.
3. Use the SEO Links Generator settings page to change the settings for SEO Links Generator.
4. Enjoy the automatically inserted links.

== Screenshots ==

1. Plugin settings page

== License ==

This file is part of SEO Links Generator.

SEO Links Generator is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

SEO Links Generator is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with SEO Links Generator. If not, see <http://www.gnu.org/licenses/>.

== Frequently Asked Questions ==

**What's the difference between SEO Links Generator and SEO Smart Links?**

SEO Links Generator is based on SEO Smart Links 2.7.6 by Vladimir Prelovac. SEO Links Generator has a redesigned settings page with the settings grouped under internal links, custom keywords, excluding and targeting. Furthermore is SEO Links Generator completely translatable, so you can easily translate it to you native language (please contact me if you have a translation finished).

**How do I enable SEO Links Generator cache?**

The only thing you need to do is enabling WordPress cache inside wp-config.php:

define(ENABLE_CACHE, true);

Make a backup of this file before you make any changes!

**How can I review the keyword generated and add exclusions?**

Unfortunately it is only possible to view the keywords on the posts or pages self. There is no list of generated keywords. You can add exclusions on the settings page (Settings > SEO Links Generator).

**What is "allow self linking"?**

When allow self linking is enabled, it is possible that SEO Links Generator creates links on a page to the page itself. When allow self linking is turned off SEO Links Generator will only genrate links to other posts or pages.

**Why would I want to specify exclusions in the excluding section? In the previous sections I've specified keywords and 'Enabled' posts only.**

It could be possible you want specific keywords to auto link, but not on specific posts or pages. Futhermore you don't need to specifiy keywords for SEO Links Generator to work, but you can always exclude keywords if needed.

**What does the targeting section do?**

In the Internal Links section you can enable SEO Links Generator for different post types (on which post types should there be linked keywords?). In the Targeting section you can enable which post types SEO Links Generator should link to.

**When will future x included or bug y fixed?**

At the moment I have little spare time to work on this plugin. Thus future bug fixes and requests could take some time.