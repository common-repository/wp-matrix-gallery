=== Matrix Gallery ===

Contributors: wpslideshow.com
Author URI:http://wpslideshow.com/matrix-gallery/
Tags: wp gallery, gallery, free gallery, video gallery
Requires at least: 3.0
Tested up to: 3.4.1
Stable tag: trunk

Matrix Gallery can be shown in the posts using the short code [matrix]. You can display this gallery multiple instances. It is also possible to display specific categories and images with their ID's in this slideshow.

== Description ==

Warning: Please take backup of your images before you update to the new version. The auto update may cause loss of images. You need to remove your existing gallery and add new one.

Matrix Gallery can be shown in the posts using the short code [matrix]. You can display this gallery multiple instances. It is also possible to display specific categories and images with their ID's in this slideshow.

**Features**

* Customizable gallery width and gallery height
* Customizable image width
* Customizable slidehsow Title and description
* Customizable auto play time
* Transition Time
* Customizable slide interval
* Customizable Image scalling



Installation Video: http://www.youtube.com/embed/WdFTgivoens

For working demo : http://wpslideshow.com/matrix-gallery/

Requirements/Restrictions:
-------------------------
 * Works with Wordpress 3.0, WPMU (Wordpress 3.0+ is highly recommended)
 * PHP5 


== Installation ==

1. Install automatically through the 'Plugins', 'Add New' menu in WordPress, or upload the 'wp-matrix-gallery' folder to the '/wp-content/plugins/' directory. 

2. Activate the plugin through the 'Plugins' menu in WordPress. Look for the settings under "Matrix Gallery" link  on left side menu to configure the Options. 


= short codes to use in content =

* <code>[matrix]</code> - Use this short code in the content / post to display all images under all categories which are not disabled.

* <code>[matrix cats=2,3]</code> - Use this short code in the content / post to display all images under the categories with ID's 2,3.

* <code>[matrix imgs=1,2,3]</code> - Use this short code in the content / post to display images which has ID's 1,2,3.

= short codes to use in template =

* <code><?php echo do_shortcode('[matrix]');?></code> - Use this short code in the template (php file) to display all images under all categories which are not disabled.

* <code><?php echo do_shortcode('[matrix cats=2,3]');?></code> - Use this short code in the template (php file) to display all images under the categories with ID's 2,3.

* <code><?php echo do_shortcode('[matrix imgs=1,2,3]');?></code> - Use this short code in the template (php file) to display images which has ID's 1,2,3.

If you facing any issues in using this plugin please contact our support at addons@wpslideshow.com

Installation Video: http://www.youtube.com/embed/WdFTgivoens

For working demo : http://wpslideshow.com/matrix-gallery/

== Screenshots ==

1. screenshot-1.jpg - Gallery front end. 

2. screenshot-2.gif - Add new album / category.

3. screenshot-3.gif - Edit image.

4. screenshot-4.gif - bulk upload.

5. screenshot-5.gif - edit album / category.

6. screenshot-6.gif - short code to be placed in the content.




== change log ==

=1.0=
Initial released version


=2.0=
This is entirely new build. It is not possible to upgrade from old version to this version. You need to uninstall old version an dinstall the new version.

=2.2=
Fixed security bugs