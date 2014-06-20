﻿=== Advanced post slider ===
Contributors: digontoahsan
Donate link: 
Tags: post slider, slider, slideshow, wordpress slideshow, logo scroller, testimonial scroller, banner rotator, recent post slider, bxslider, sidebar slideshow, posts, post, image, image slideshow,
Requires at least: 3.0.1
Tested up to: 3.9.1
Stable tag: 2.0
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Responsive slideshow plugin powered with three built-in templates, lots of easy customizable options and many more to explore.

== Description ==

Unlimited number of slideshow in a single page or post with different sets of options like post type, category, effect, navigation type.
Create slideshow with single or multiple images per slide, rotate your banner or client logo at sidebar; scroll your testimonial with custom link.

<strong>Click here for <a target="_blank" href="http://wpcue.com/plugins/advanced-post-slider/template-one-demo/">demo</a></strong>

= Key Feature =

* You can create multiple slideshow with different options at single page or post.
* Three built-in design format and each have a predefined optionset.
* You can customize this in many ways withour changing code.
* Supports post,custom post type and even page content
* Easy option for adjusting slide container width, height, background color, border and box-shadow. You can easily turn on/off border and box-shadow
* Ability to control excerpt length for each slideshow
* Cross browser compatibility

Visit <a target="_blank" href="http://www.wpcue.com/plugins/advanced-post-slider/">www.wpcue.com/</a> for more

== Installation ==

Using the WordPress dashboard

1. Login to admin panel
2. Go to Plugins
3. Select Add New
4. Search Advanced post slider
5. Select Install Now
6. Select Activate Plugin

Manual

1. Download the plugin and extract the files
2. Upload the directory "advanced-post-slider" to your wp-content/plugins/ directory
3. Activate the plugin through the 'Plugins' menu in WordPress
4. Check the "Adv. Slider" Tab created by this plugins for manage options

Use shortcode [advps-slideshow optset="optset ID"] at admin panel post/page edit screen where optset ID is the id of the option set. You will get the id of optoin set at the top right corner of each option set from admin panel.

Use WordPress function "do_shortcode" for use in template or theme PHP file.
`<?php echo do_shortcode( '[advps-slideshow optset="1"]' ); ?>`

== Frequently Asked Questions ==

= Where do I submit a question? =

Dont have any FAQ for now.

== Screenshots ==

1. Templates and options
2. Template one example
3. Template one example
4. Template one example
5. Carousel & Ticker with template one
6. Template three example
7. Template three example

== Changelog ==

= 1.0 =
* First version.

= 1.1 = 
* Option for title tag
* Option for link target
* Remove auto exclude current post

= 1.2 =
* Fix for exclude option

= 2.0 =
* Important Upgrade notice
	* Dont perform automatic upgrade now. There is a bug and I will fix it ASAP. Rather than upgrading automatically by clicking update now just deactivate the plugin then delete it from admin panel then re-install version 2 again.
    
* Before upgrade
	* Database structure of Advanced post slider is changed. Your previous option set and settings will be lost.
    * jQuery plugin is changed to bxSlider. jQuery Cycle plugin lover may consider not to update.
    
* Enhancements & New feature
	* Responsive
	* Thumbnail pagination 
	* Carousel & Ticker mode for all templates
	* Multiple slide for all template
	* Improved design for template one
	* Improved admin UI


== Upgrade Notice ==
* Important Upgrade notice
	* Dont perform automatic upgrade now. There is a bug and I will fix it ASAP. Rather than upgrading automatically by clicking update now just deactivate the plugin then delete it from admin panel then re-install version 2 again.
    
* Before upgrade
	* Database structure of Advanced post slider is changed. Your previous option set and settings will be lost.
    * jQuery plugin is changed to bxSlider. jQuery Cycle plugin lover may consider not to update.