Menu<>Pages
Presentase :_
== Installation ==

View <a href="https://mediaelementjs.com/">MediaElementjs.com</a> for more information.

1. Upload the `media-element-html5-video-and-audio-player` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the `Plugins` menu in WordPress
3. Use the `[video]` or `[audio]` shortcode in your post or page with the options on the front page.

== Changelog ==

= 2.2.5 =
* Update to 2.2.5 codebase
* Support for true fullscreen in Chrome and Firefox (in addition to Safari)
* Support for 100% sizing

= 2.1.7 =
* Skin selector (default, WMP, TED)
* Audio height and width
* Leave off the extension on the src attribute and files will be automatically detected

= 2.1.4 = 
* Updated to latest MediaElement.js code
* Changed scripts to use wp_enqueue_script("mediaelementjs-scripts")
* Changed styles to use wp_enqueue_style("mediaelementjs-styles")
* Added [mejsaudio] and [mejsvideo] as valid short codes. Wordpress's Jetpack will now take over [audio]

= 2.0.6.2 = 
* Fixed a problem with Wordpress SVN

= 2.0.6 = 
* Updated to 2.0.6 codebase

= 2.0.5 = 
* Lots of minor changes to JS code
* better IE6 support

= 2.0.4 = 
* Plugin fix

= 2.0.3 = 
* Silverlight fix

= 2.0.2 = 
* Updated to 2.0.2 MEjs code

= 2.0.1.2 =
* Loop fix
* Video for Everybody Syntax (Works even when JavaScript is turned off)

= 2.0.1.1 =
* Autoplay fix

= 2.0.1 =
* Updated to 2.0.1 version

= 1.1.5 =
* Updated to 1.1.5 version
* Added options to turn controls on/off
* Added loop option

= 1.1.2 =
* Updated to 1.1.2 version
* adds captions support and new style

= 1.1.0 =
* Updated to 1.1 of player

= 1.0.1 =
* Fixed URL bug
* Fixed non-src bugs

= 1.0 =
* First release.

== Upgrade Notice ==

None

== Frequently Asked Questions ==

= Where can I find out more? =

Check out <a href="https://mediaelementjs.com/">mediaElementjs.com</a> for more examples

= What does this get me over other HTML5 players? =

Most HTML5 players offer one player to modern browsers and then a competely separate Flash player to older browser. This creates an inconsistent look and functionality. 

Instead, MediaElement.js upgrades older browsers, using Flash to mimic the entire HTML5 Media API. Then once all the browsers have something that looks like HTML5 Media, we build a consistent player on top using just HTML and CSS.

See original blog post at <a href="http://johndyer.name/post/MediaElement-js-a-magic-unicorn-HTML5-video-library.aspx">johndyer.name</a> for a full explanation of MediaElement.js

== Screenshots  ==

1. Video player
