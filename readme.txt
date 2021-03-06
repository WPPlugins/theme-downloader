=== Plugin Name ===
Contributors: georgestephanis
Donate link: https://www.charitywater.org/donate
Tags: Theme, Download, Zip
Requires at least: 3.4
Tested up to: 3.9
Stable tag: 1.1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A handy dandy plugin that tries to let you download any installed theme as a zip file.

== Description ==

Most themes are licensed under the GPL, which makes it completely legal for you to do whatever you like with them, so long as you don't restrict what other people, in turn, can do with them.  This is a type of copyleft license, and it means that you are free to redistribute any GPL-compliant themes any way you like!

Unfortunately, it's often hard to actually do.  While it's easy to upload a theme as a zip file, it's difficult to get the theme back afterwards!  This plugin aims to make that a bit easier.

If your server is capable of making Zip archives, and your user account has the `edit_themes` capability, then this plugin will let you download any of your themes -- including any modifications you've made to the code of it -- as a Zip file that you can then reinstall on any other WordPress site!

Enjoy!  :)

P.S. -- If the author of your theme didn't license it on a GPL-compliant license, make sure you're not breaking any licensing terms by what you do with the theme once you've downloaded it!

== Installation ==

1. Install and activate the plugin via the WordPress Plugin Installer.
2. Go to the Manage Themes screen, and use the newly added download links!
3. There is no step three!

== Frequently Asked Questions ==

= Why won't it display the download links? =

Well, there's two possible reasons.  For one, your server may not be able to create zip archives.  If that's the case, there's not much you can do.

The second possible reason is if you don't have the proper capabilities.  If you don't have the `edit_themes` capability, you can't download them either.  Sorry!

== Changelog ==

= 1.1 =
* Add compatability for WordPress 3.8 and 3.9, as they dropped a filter when implementing the new Theme Experience (THX-38)
* See: https://core.trac.wordpress.org/ticket/26930

= 1.0.1 =
* Added some code in r721178 to account for Network Admin Themes page passing different arguments to the theme_action_links filter.

= 1.0 =
* Initial release.
