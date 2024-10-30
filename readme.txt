=== Lean Media ===
Contributors: codix, mohanjith, WPMUDEV
Donate link: http://twitter.com/codemasteroy
Tags: media, thumbnail, storage, save
Requires at least: 3.4.1
Tested up to: 3.5
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Save storage space by deleting large image files after generating thumbnails.

== Description ==

With easy access to high resolution digital cameras everyone has access to very large images. Your users
are probably uploading them and using up lot of storage space for you. However these images are hardly
ever used.

Lean Media allows you to automatically delete the very large image files after generating thumbnails. Largest
thumbnail is saved in place of the original image just in case you decide to generate thumbnails again. 

If the users are kind enough to upload small images Lean Media leaves such images intact.

== Installation ==

1. Upload `lean-media` directory to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to 'Settings' -> 'Media' and make sure 'Delete Large Images' is checked

== Frequently Asked Questions ==

= What if I decide to change the thumnail sizes? Can I regenerate thumbnails? =

Yes! However if the thumbnail sizes are larger than the largerst thumnail it might not look pretty

= I have a suggestion! =

Sure! Write to us at [hello@codemaster.fi](mailto:hello@codemaster.fi) with your suggestions.

== Notes & Credits ==

This plugin is written by [S H Mohanjith](http://mohanjith.com/).

You should follow us on Twitter *[here](http://twitter.com/codemasteroy)*.

== Screenshots ==

1. Media Settings

== Changelog ==

= 1.0 =
* Deletes large file after thumbnail generation
* To allow future thumbnail generation largest thumbnail is copied with the same name as original file

== Upgrade Notice ==

= 1.0 =
You just installed, why are you trying to update?
