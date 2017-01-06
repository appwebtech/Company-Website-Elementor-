<div align="center">
<h1>Company Website</h1> 
<h2>Software Development Documentation</h2>
  <h3>
    <a href="http://theappwebtech.com">
      Appwebtech
    </a>
  </h3>
</div>

<div align="center">
  <sub>Developed and Designed by
  <a href="#">Joseph M Mwania</a> for
  <a href="#http://theappwebtech.com">
    Appwebtech
  </a>
</div>

<h2>Table of Contents</h2>
- [Introduction](#introduction)
- [Why Wordpress](#why-wordpress)
- [Technical Requirements](#technical-requirements)
  - [Elementor](#elementor)
  - [WPGlobus for WPBakery Visual Composer](#wpglobus-for-wpbakery-visual Composer)
  - [Google Maps Widget](#google-maps-widget)
  - [Simple Light Box](#simple-light-box)
  - [PHP](#php)
  - [jQuery](#jquery)
  - [Photoshop](#photoshop)
  - [Deployment instructions](#deployment-instructions)
  - [Developer](#developer)
  - [Contacts](#contacts)


# Introduction

Chances are that if you have landed on this page via Google searching for CMS platforms and open-source developers, then you already have heard of Wordpress and lucky you because here you got both. An open-source fanatic with a documented code. 

Firstly, I would like to point out that code, whether basic or sophisticated like a mixture of Lisp and Intercal, it should bear documentation if it so happens that an application is built from it. All this hype from programmers online hangouts that (**Real programmers don't document their programs. Documentation is for simpletons who can't read listings or the object code from dumps**) doesn't make sense if someone is engaging with clients who want to know how their software works. 

Secondly, this documentation is not written to learn how to use the website. Everyone at this age and time can browse a website and download or purchase stuff online. This is a brief synopsis of how I created the software and with what technologies. Important! I get requested for it a lot by nontechnicals, but I still stand with Eric S. Raymond's quote. *if they have to read documentation to use it you designed it wrong.*  

Since it's release in 2003, Wordpress has evolved tremendously and now has become one of the best web technologies in building websites. 
At the time of writing, Wordpress powers close to 75 million websites. So what is it? 

Wordpress is an open-source [Content Management System (CMS)](https://en.wikipedia.org/wiki/WordPress) that uses [Hypertext Preprocessor (PHP)](https://en.wikipedia.org/wiki/PHP) for its BackEnd (server-side) system and [MySQL](https://en.wikipedia.org/wiki/MySQL) to manage it's databases (DB). PHP is a server-side scripting language which is amazing in web development; this is due to it's flexibility to be embedded in [HTML](https://en.wikipedia.org/wiki/HTML), more or less the way [Ruby](https://en.wikipedia.org/wiki/Ruby_on_Rails) is embedded in Rails. PHP is very versatile and compatible across many browsers, web servers and operating systems. The preference of using it for server-side systems has grown and will continue due to it's de-facto pro-bono policy. Same applies to MySQL.

Wordpress uses MySQL to manage it's DB's and PHP renders data from the server to the frontend. MySQL is an RDBMS and most of it's functionalities are open-source. It's a main component of [LAMP](https://en.wikipedia.org/wiki/LAMP_(software_bundle)) open-source web application software stack. 

Below is a snapshot of the DB I used. It can be queried, searched and exported to other servers. That is the main reason I used SoC to have a reputable external source to process payments. Actually, [WooCommerce](https://woocommerce.com/) will not process payments but will direct them to be processed by [Paypal](https://www.paypal.com/).
<hr>
![screen shot 2017-01-06 at 17 55 00](https://cloud.githubusercontent.com/assets/20464709/21725638/907f875e-d439-11e6-8b18-9b8c599facde.png)
<hr>

There are a myriad of reason as to why I love using open-source software in design and development. Compelling advatanges gravitate towards the following factors which are quite intuitive;
* Security
* Customizability
* Freedom
* Auditability
* Ready Support (Bug fixes are timely)
* Try and discard if you dont like.
* Quality etc etc


# Why Wordpress?

Wordpress is great in building almost any website. A developer can design a theme and sell to whomever wants to buy, eg [themeforest](https://themeforest.net/search?utf8=%E2%9C%93&term=ecommerce&as=0&referrer=homepage), etc. Themes vary from free downloadables to a cost that would vary from  $2, see [here](https://themeforest.net/item/sketch-and-css-bridging-the-gap/15284085?s_rank=1) up to a cost way beyond $999, like  [this](https://themeforest.net/item/fightclub-fight-fitness-club-psd-template/12237033?s_rank=17). It all depends really on what your website entails, your target audience, security features, design, etc. 

Wordpress, [Joomla](https://en.wikipedia.org/wiki/Joomla) and [Drupal](https://en.wikipedia.org/wiki/Drupal) are the trending CMS systems in the planet at the time of writing. Their ability to deliver projects within the given time frame coupled with their versatility to use functionalities which reside in plugins have led to their growth and support globally. 
 

# Technical Requirements


## Elementor

### Elementor [![Build Status](https://travis-ci.org/pojome/elementor.svg?branch=master)](https://travis-ci.org/pojome/elementor) [![Coverage Status](https://coveralls.io/repos/github/pojome/elementor/badge.svg?branch=master)](https://coveralls.io/github/pojome/elementor?branch=pojome/elementor) [![Dependency Status](https://david-dm.org/pojome/elementor/dev-status.svg)](https://david-dm.org/pojome/elementor#info=devDependencies) [![WordPress](https://img.shields.io/wordpress/v/elementor.svg?style=flat-square)](https://wordpress.org/plugins/elementor/) [![WordPress](https://img.shields.io/wordpress/plugin/r/elementor.svg?style=flat-square)](https://wordpress.org/plugins/elementor/) [![WordPress](https://img.shields.io/wordpress/plugin/v/elementor.svg?style=flat-square)](https://wordpress.org/plugins/elementor/) [![WordPress](https://img.shields.io/wordpress/plugin/dt/elementor.svg?style=flat-square)](https://wordpress.org/plugins/elementor/) [![Built with Grunt](https://cdn.gruntjs.com/builtwith.svg)](http://gruntjs.com/)

**Contributors:** [pojo.me](https://profiles.wordpress.org/pojo.me), [KingYes](https://profiles.wordpress.org/KingYes), [ariel.k](https://profiles.wordpress.org/ariel.k), [jzaltzberg](https://profiles.wordpress.org/jzaltzberg), [yehudah](https://profiles.wordpress.org/yehudah), [mati1000](https://profiles.wordpress.org/mati1000), [pojosh](https://profiles.wordpress.org/pojosh)  
**Tags:** page builder, editor, elementor, builder, visual editor, front-end editor, design, drag and drop builder, front-end builder, landing page, page builder plugin, site builder, template builder, visual builder, website builder, wysiwyg  
**Requires at least:** 4.4  
**Tested up to:** 4.7  
**Stable tag:** 1.0.10  
**License:** GPLv3  
**License URI:** https://www.gnu.org/licenses/gpl-3.0.html  

### Faster. Much faster. ###
Instant reaction was a key feature we wanted to achieve. Instant drag & drop, instant live edit, instant page load. The speed of Elementor is not matched by any other page builder, free or paid. This makes the interface fun and easy to work with, as well as reduces the time it takes to design.

### Live design. Truly live. ###
Never again work on the backend and guess what the frontend will look like. With Elementor, you edit the page and simultaneously see exactly how it looks like. Elementor features live editing that is truly live, with no need to press update or go to preview mode.

### Surprises you won't see anywhere else. ###
Create pages that have "the designer touch", by including unique features like box shadows, background overlays, hover and entrance animations, advanced buttons and more. We worked hard to create the perfect balance between full design capabilities and an intuitive and clean interface. You no longer need to use code, HTML, CSS or shortcode.

### NEW! Template Library. ###
We've added **Library**, which includes a collection of 20+ beautiful templates, made for you by our top notch designers. You can also save your own pages and sections, and reuse them on different pages, or export them to whole different websites.

### NEW! Mobile Editing. ###
Elementor comes with an exclusive toolset, that lets you create truly a responsive website in a whole new and visual way. From different font size per device, to reverse column ordering, this is the most powerful solution for creating perfect mobile pages.

### 28 widgets and counting ###
We packed 28 of the most useful widgets into Elementor. True, that's way more than we had to offer, but we wanted to spare no widget from you, so you can reach the top of your design capabilities.



## WPGlobus for WPBakery Visual Composer 

**Contributors:** alexgff, tivnetinc, tivnet  
**Donate link:** http://www.wpglobus.com/  
**Tags:** globalization, i18n, international, l10n, visual composer, localization, multilanguage, multilingual, translate, WPGlobus  
**Requires at least:** 4.0  
**Tested up to:** 4.2.3
**Stable tag:** trunk  
**License:** GPLv2
**License URI:** https://github.com/WPGlobus/wpglobus-for-wpbakery-visual-composer/blob/master/LICENSE  

### Description 

**WPGlobus for WPBakery Visual Composer** is an extension to the WPGlobus plugin.

> **NOTE:** You need to install and activate the [WPGlobus Multilingual Plugin](https://wordpress.org/plugins/wpglobus/) version 1.0.14 or later before installing the WPGlobus for WPBakery Visual Composer extension.

#### More info

* [WPGlobus for WPBakery Visual Composer home page](http://www.wpglobus.com/extensions-archive/wpglobus-for-wpbakery-visual-composer-archive/).
* [GitHub code repository](https://github.com/WPGlobus/wpglobus-for-wpbakery-visual-composer).

### Installation 

You can install this plugin directly from your WordPress dashboard:

1. Go to the *Plugins* menu and click *Add New*.
1. Search for *WPGlobus for WPBakery Visual Composer*.
1. Click *Install Now* next to the *WPGlobus for WPBakery Visual Composer* plugin.
1. Activate the plugin.

Alternatively, see the guide to [Manually Installing Plugins](http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation).

### Frequently Asked Questions 

#### How do I contribute to WPGlobus for WPBakery Visual Composer? 

We appreciate all contributions, ideas, critique, and help.

* To speed up our development, please report bugs, with reproduction steps on [WPGlobus for WPBakery Visual Composer GitHub](https://github.com/WPGlobus/wpglobus-for-wpbakery-visual-composer).
* Plugin and theme authors: please try WPGlobus for WPBakery Visual Composer and let us know if you find any compatibility problems.
* Contact us directly on [WPGlobus.com](http://www.wpglobus.com/contact-us/).

#### More info? 

Please check out the [WPGlobus Website](http://www.wpglobus.com/extensions-archive/wpglobus-for-wpbakery-visual-composer-archive/) for additional information.

### Screenshots 

####  Plugin admin interface. 
![Plugin admin interface.](https://raw.githubusercontent.com/WPGlobus/wpglobus-for-wpbakery-visual-composer/master/assets/screenshot-1.png)

### Changelog 

#### 1.0.0 
* Initial release


## Google Maps Widget

### Description
Bring the world into your application, with the Google Maps widget!

### Typical usage scenario

Giving a visual representation of an address.
Showing an overview where all your branches/members/clients/orders/etc. are.
 
### Features and limitations
Tap directly into all the power of Google Maps.
Easy to implement.
No route planning or advanced features yet.

### Dependencies
Mendix 5.x Environment

### Configuration
One of the most important things to keep in mind when implementing this widget is the Google Maps terms of use. These can be found here: Terms of Use. [Chapter 9.1 is especially important](https://developers.google.com/maps/terms#9-license-requirements).

        Free, Public Accessibility to Your Maps API Implementation. Your Maps API Implementation must be generally accessible to users without charge. You may require users to log in to your Maps API Implementation if you do not require users to pay a fee. U nless you have entered into a separate written agreement with Google or obtained Google's written permission , your Maps API Implementation must not:

        (a) require a fee-based subscription or other fee-based restricted access; or
        (b) operate only behind a firewall or only on an internal network (except during the development and testing phase).


There are 3 use-cases for which this widget can be used.

        Outside a dataview: Will just retrieve the objects specified and show them on the map.
        Inside a dataview not matching the Objects property: Will show the objects specified, can use '[%CurrentObject%]' in XPath Constraint.
        Inside a dataview matching the Objects property: Will show the objects specified, can NOT use '[%CurrentObject%]'. Can set up the dataview to listen to a matching datagrid. If 'Pan to context' is set to true, it will focus on the marker of the object that is selected in the datagrid.

To finish up, just enter the correct values into the widget. For more information on the different input properties, read below.

### Maps API Access Key

The Google Maps Javascript API v3 does not require an API key to function properly. However, Google strongly encourages you to load the Maps API using an APIs Console key which allows you to monitor your application's Maps API usage.
You can get an API key by following [the steps provided here](https://developers.google.com/maps/documentation/javascript/get-api-key)


## Simple Light Box

Touch-friendly image lightbox for mobile and desktop with jQuery

### Features
* responsive
* touchfriendly
* swipe gestures for next/previous image
* easy to install, easy to use
* minimalistic
* Only some css is included. You can change the style like you want!
* lots of options
* preloading next and previous image
* Android, iOs and Windows phone support
* CSS3 Transitions with fallback for older browsers
* Works in every modern Browser, even in IE 9+
* Can use jQuery 1.x,2.x and 3.x
* Keyboard support

### Installation
```sh
//Bower
bower install simplelightbox

//NPM
npm install simplelightbox
```

### Usage
Simple include simplelightbox.css and simple-lightbox.js to your page
```javascript
var lightbox = $('.gallery a').simpleLightbox(options);
```

### JavaScript Options
| Property | Default | Type | Description |
| -------- | ------- | ---- | ----------- |
| overlay | true | bool | show an overlay or not |
| spinner | true | bool | show spinner or not |
| nav | true | bool | show arrow-navigation or not |
| navText | ['&larr;','&rarr;'] | array | text or html for the navigation arrows |
| captions | true | bool | show captions if availabled or not |
| captionSelector | 'img' | string | set the element where the caption is. Set it to "self" for the A-Tag itself |
| captionType | 'attr' | string | how to get the caption. You can choose between attr, data or text |
| captionsData | title | string | get the caption from given attribute |
| captionPosition | 'bottom' | string | the position of the caption. Options are top, bottom or outside (note that outside can be outside the visible viewport!) |
| captionDelay | 0 | int | adds a delay before the caption shows (in ms) |
| close | true | bool | show the close button or not |
| closeText | '×' | string | text or html for the close button |
| swipeClose | true | bool | swipe up or down to close gallery |
| showCounter | true | bool | show current image index or not |
| fileExt | 'png&#124;jpg&#124;jpeg&#124;gif' | regexp or false | list of fileextensions the plugin works with or false for disable the check |
| animationSpeed | 250 | int | how long takes the slide animation |
| animationSlide | true | bool | weather to slide in new photos or not, disable to fade |
| preloading | true | bool | allows preloading next und previous images |
| enableKeyboard | true | bool | allow keyboard arrow navigation and close with ESC key |
| loop | true | bool | enables looping through images |
| rel | false | mixed | group images by rel attribute of link with same selector.
| docClose | true | bool | closes the lightbox when clicking outside |
| swipeTolerance | 50 | int | how much pixel you have to swipe, until next or previous image |
| className: | 'simple-lightbox' | string | adds a class to the wrapper of the lightbox |
| widthRatio: | 0.8 | float | Ratio of image width to screen width |
| heightRatio: | 0.9 | float | Ratio of image height to screen height |
| disableRightClick | false | bool | disable rightclick on image or not |
| disableScroll | true | bool | stop scrolling page if lightbox is opened |
| alertError | true | bool | show an alert, if image was not found. If false error will be ignored |
| alertErrorMessage | 'Image not found, next image will be loaded' | string | the message displayed if image was not found |
| additionalHtml | false | string | Additional HTML showing inside every image. Usefull for watermark etc. If false nothing is added |
| history | true | bool | enable history back closes lightbox instead of reloading the page |

### Events
| Name | Description |
| ---- | ----------- |
| show.simplelightbox | this event fires before the lightbox opens |
| shown.simplelightbox | this event fires after the lightbox was opened |
| close.simplelightbox | this event fires before the lightbox closes |
| closed.simplelightbox | this event fires after the lightbox was closed |
| change.simplelightbox | this event fires before image changes |
| changed.simplelightbox | this event fires after image was changed |
| next.simplelightbox | this event fires before next image arrives |
| nextDone.simplelightbox | this event fires after next image was arrived |
| prev.simplelightbox | this event fires before previous image arrives |
| prevDone.simplelightbox | this event fires after previous image was arrived |
| nextImageLoaded.simplelightbox | this event fires after next image was loaded (if preload activated) |
| prevImageLoaded.simplelightbox | this event fires after previous image was loaded (if preload activated) |
| error.simplelightbox | this event fires on image load error |

**Example**  
```javascript
$('.gallery a').on('open.simplelightbox', function () {
  // do something…
});

$('.gallery a').on('error.simplelightbox', function (e) {
  console.log(e); // some usefull information
});
```

### Public Methods
| Name | Description |
| ---- | ----------- |
| open | Opens the lightbox with an given jQuery Element |
| close | Closes current openend Lightbox |
| next | Go to next image |
| prev | Go to previous image |
| destroy | Destroys the instance of  the lightbox |
| refresh | Destroys and reinitilized the lightbox, needed for eg. Ajax Calls, or after dom manipulations |

**Example**  
```javascript
var gallery = $('.gallery a').simpleLightbox();

gallery.next(); // Next Image
```

### Multiple Lightboxes on one page
You can have multiple lightboxes on one page, if you give them different selectors. Here is a small example:
```javascript
var lightbox1 = $('.lighbox-1 a').simpleLightbox();
var lightbox2 = $('.lighbox-2 a').simpleLightbox();
```

## PHP

This website uses PHP as it's backend system for it's database and server client functionalties. The beauty of PHP is it's ability to be embedded with HTML. The server in this website uses CGI protocol to process PHP code and render the website functionalities. 

## jQuery

jQuery is a Javascript library that enhances script composition from the designer/developer coding environment. It's super fast and amazing at event handling, animation, document traversal, Ajax and if you write API's constantly, then jQuery can come in handy instead of using vanilla javascript.

It's DOM element selection has lead to insights in creating other javascript frameworks tailored at specific needs. It has many contributors with over 6000 commits on it's GitHub page at the time of writing, and big multinationals like Nokia and Microsoft bundle it on their platforms eg ASP.NET, AJAX, Visual Studio etc.

Using jQuery to code has been very rewarding as it solves many a problem with less pain saving a lot of time and thus enhancing productivity in the long run.


## Photoshop

It's no doubt that Adobe Photoshop remains the best raster graphics editor on the planet. It's ability to use RGB, CMYK, duotone, etc coupled with the great variety of image extensions makes it the best option to edit images professionally. 

I have used it previously for image sizing and for enhancing vivid display accross platforms from smart tv's to smart phones. In this project, large images have been targeted for big displays like desktops whilst small displays have images of reduced dimensions in pixels.

I tweak images to ensure that pixels are not lost when switching viewports and that the image extensions like **.jpeg** and **.png** are well saved to curb image degradation. 

## Deployment instructions

Deploy to a server which supports Wordpress like Godaddy, HostGator etc. HostGator is more speedy in loading pages imo than other websites.

In most cases I code locally and later upload to my cPanel. I will try andupload this website and fight the urge of pulling it down. (For some reason many people buy demo websites and request that they get pulled down. Let's cross fingures to thwart that.) 

## Developer

Joseph Musembi Mwania

## Contacts

http://www.theappwebtech.com/

https://github.com/appwebtech

https://twitter.com/appwebtech

https://www.facebook.com/theappwebtech/

https://it.pinterest.com/appwebtech/




