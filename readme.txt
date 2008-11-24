=== Exhibit to WP Gallery ===
Contributors: ulfben
Donate link: http://www.amazon.com/gp/registry/wishlist/2QB6SQ5XX2U0N/105-3209188-5640446?reveal=unpurchased&filter=all&sort=priority&layout=standard&x=11&y=10
Tags: exhibit, gallery, convert, migrate, owen, winkler,  
Requires at least: 2.6.3
Tested up to: 2.6.3
Stable tag: 0.001

Convert your ancient Exhibit 1.1b galleries to modern WordPress attachments / galleries

== Description ==
Exhibit to WP Gallery can convert your *ancient* [Exhibit 1.1b](http://redalt.com/downloads/)-galleries to normal WordPress attachments. Requires a linux host.

* Captions and image order will be transferred.
* All files will be *copied* to your upload folder. (use [Custom Upload Dir](http://wordpress.org/extend/plugins/custom-upload-dir/) for better structure!)
* New thumbnails will be generated according to your WordPress settings
* Lastly, the plugin will add '&lt;br /&gt; [[gallery]](http://codex.wordpress.org/Using_the_gallery_shortcode)' to the end of each post it touches. 
* The plugin can list all posts currently using Exhibit, making it easy to visit them and make sure all went OK.

The conversion is slow and painfull; the script might timeout. Therefore it is built so you can do it in chunks. *Tip:* Start with a single post and a few rows to make sure everything works before running through the entire table.

Check the [screenshots](http://wordpress.org/extend/plugins/exhibit-to-wp-gallery/screenshots/) out for more info!

== Installation ==
[Backup](http://codex.wordpress.org/WordPress_Backups) both the filesystem and database before running the conversion!

1. Make sure you're hosted on a linux server. (requires [file](http://en.wikipedia.org/wiki/File_(Unix))
1. Extract `exhibit-to-wp-gallery.php` and transfer it to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Visit "Exhibit to WP Gallery" in "Settings" and follow the instructions.

I recommend you read the source code of the plugin before running it. It has only been tested on one blog, and might make assumptions that doesn't hold true for your installation.

== Frequently Asked Questions ==


== Screenshots ==

1. The plugin interface

2. The plugin attempts error checking and avoids duplicating entries

3. Explaining the options and features

== Other Notes ==
Copyright (C) 2008 Ulf Benjaminsson (ulf a t ulfben d o t com).

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA