=== Image Upload for BBPress ===
Contributors: hearken
Donate link: https://potentplugins.com/donate/?utm_source=image-upload-for-bbpress&utm_medium=link&utm_campaign=wp-plugin-readme-donate-link
Tags: bbpress, image, images, media
Requires at least: 3.5
Tested up to: 4.4
Stable tag: 1.1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Upload inline images to BBPress forum topics and replies.

== Description ==

This plugin enables the TinyMCE WYSIWYG editor for BBPress forum topics and replies and adds a button to the editor's "Insert/edit image" dialog that allows forum users to upload images from their computer and insert them inline into their posts.

A [pro version](http://potentplugins.com/downloads/image-upload-for-bbpress-pro-wordpress-plugin/?utm_source=image-upload-for-bbpress&utm_medium=link&utm_campaign=wp-repo-upgrade-link) with the following additional features is also available:

* Change the directory where uploaded images are stored.
* Limit which user roles are permitted to upload images.
* Limit the number of uploaded images allowed per post.
* Automatically downsize images to fit specified maximum dimensions.
* Convert all uploaded images to the same image format, if desired.
* Set PNG and JPEG compression levels so images take up less disk space.
* View total image count and file size statistics.

== Installation ==

1. Click "Plugins" > "Add New" in the WordPress admin menu.
1. Search for "Image Upload for BBPress".
1. Click "Install Now".
1. Click "Activate Plugin".

Alternatively, you can manually upload the plugin to your wp-content/plugins directory.

== Frequently Asked Questions ==

== Screenshots ==

1. The Image toolbar icon in the TinyMCE editor for forum topics and replies.
2. The Browse button in the Image dialog, which allows the user to select and upload an image from their computer for inline insertion into their forum topic or reply.

== Changelog ==

= 1.1.0 =
* Added support for rotations based on EXIF orientation data in JPEG images
* Added cleanup feature to remove unnecessary files
* Added plain text conversion when pasting formatted text into the WYSIWYG editor
* Added attempt to increase PHP memory limit before image processing


= 1.0.8 =
* Fixed bug affecting multi-domain sites

= 1.0.7 =
* Fixed bug with non-root-URL WordPress installations

= 1.0.5 =
* Hide image caption field

= 1.0.4 =
* Fixed bug with uploads by anonymous users

= 1.0 =
* Initial release

== Upgrade Notice ==