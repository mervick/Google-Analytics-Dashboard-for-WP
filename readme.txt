=== Google Analytics Dashboard for WP ===
Contributors: deconf
Donate link: https://deconf.com/donate/
Tags: google,analytics,google analytics,dashboard,analytics dashboard,google analytics dashboard,google analytics plugin,google analytics widget,tracking,universal google analytics,realtime,multisite,gadwp
Requires at least: 3.5
Tested up to: 4.4
Stable tag: 4.8.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Displays Google Analytics reports in your WordPress Dashboard. Inserts the latest Google Analytics tracking code in your pages.

== Description ==
This Google Analytics for WordPress plugin enables you to track your site using the latest Google Analytics tracking code and allows you to view key Google Analytics reports in your WordPress install.

In addition to a set of general Google Analytics reports, in-depth Page reports and in-depth Post reports allow further segmentation of your analytics data, providing performance details for each post or page from your website.

The Google Analytics tracking code is fully customizable through options and hooks, allowing advanced data collection using custom dimensions and events.    

= Google Analytics Real-Time =

Google Analytics reports, in real-time, in your dashboard screen:

- Real-time number of visitors 
- Real-time acquisition channels
- Real-time traffic sources details 

= Google Analytics Reports =

The Google Analytics reports you need, on your dashboard, in your All Posts and All Pages screens, and on site's frontend:  

- Sessions, organic searches, page views, bounce rate analytics reports
- Locations, pages, referrers, keywords analytics reports
- Traffic channels, social networks, traffic mediums, search engines analytics reports
- User access control over analytics reports

= Google Analytics Basic Tracking =

Installs the latest Google Analytics tracking code and allows full code customization:

- Switch between Universal Google Analytics and Classic Google Analytics code
- IP address anonymization
- Enhanced link attribution
- Remarketing, demographics and interests tracking
- Google AdSense linking
- Page Speed sampling rate control
- Cross domain tracking
- Exclude user roles from tracking

= Google Analytics Event Tracking =

Google Analytics Dashboard for WP enables you to easily track events like:
 
- Downloads
- Emails 
- Outbound links
- Affiliate links
- Fragment identifiers

= Google Analytics Custom Dimensions =

With Google Analytics Dashboard for WP you can use custom dimensions to track:

- Authors
- Publication year
- Categories
- User engagement

= Google Analytics Dashboard for WP on Multisite =

This plugin is fully compatible with multisite network installs, allowing three setup modes:

- Mode 1: network activated using multiple Google Analytics accounts
- Mode 2: network activated using a single Google Analytics account
- Mode 3: network deactivated using multiple Google Analytics accounts

> <strong>Google Analytics Dashboard for WP on GitHub</strong><br>
> You can submit feature requests or bugs on [Google Analytics Dashboard for WP](https://github.com/deconf/Google-Analytics-Dashboard-for-WP) repository.

= Further reading =

* Homepage of [Google Analytics Dashboard for WP](https://deconf.com/google-analytics-dashboard-wordpress/)
* Other [WordPress Plugins](https://deconf.com/wordpress/) by same author
* [Google Analytics | Partners](https://www.google.com/analytics/partners/company/5127525902581760/gadp/5629499534213120/app/5707702298738688/listing/5639274879778816) Gallery

== Installation ==

1. Upload the full google-analytics-dashboard-for-wp directory into your wp-content/plugins directory.
2. In WordPress select Plugins from your sidebar menu and activate the Google Analytics Dashboard for WP plugin.
3. Open the plugin configuration page, which is located under Google Analytics menu.
4. Authorize the plugin to connect to Google Analytics using the Authorize Plugin button.
5. Go back to the plugin configuration page, which is located under Google Analytics menu to update/set your settings.
6. Go to Google Analytics -> Tracking Code to configure/enable/disable tracking.

== Frequently Asked Questions == 

= Do I have to insert the Google Analytics tracking code manually? =

No, once the plugin is authorized and a default domain is selected the Google Analytics tracking code is automatically inserted in all webpages.

= Some settings are missing in the video tutorial =

We are constantly improving Google Analytics Dashboard for WP, sometimes the video tutorial may be a little outdated.

= How can I suggest a new feature, contribute or report a bug? =

You can submit pull requests, feature requests, translations or bug reports on [our GitHub repository](https://github.com/deconf/Google-Analytics-Dashboard-for-WP).

= Documentation, Tutorials and FAQ =

For documentation, tutorials, FAQ and videos check out: [Google Analytics Dashboard for WP documentation](https://deconf.com/google-analytics-dashboard-wordpress/).

== Screenshots ==

1. Google Analytics Dashboard for WP Blue Color
2. Google Analytics Dashboard for WP Real-Time
3. Google Analytics Dashboard for WP reports per Posts/Pages
4. Google Analytics Dashboard for WP Geo Map
5. Google Analytics Dashboard for WP Top Pages, Top Referrers and Top Searches
6. Google Analytics Dashboard for WP Traffic Overview
7. Google Analytics Dashboard for WP statistics per page on Frontend
8. Google Analytics Dashboard for WP cities on region map
9. Google Analytics Dashboard for WP Widget

== Localization ==

You can help translating this plugin on [translate.wordpress.org](https://translate.wordpress.org/projects/wp-plugins/google-analytics-dashboard-for-wp).

= GADWP Translation Editors =

Arabic - [Ahmed Majid](https://profiles.wordpress.org/ahmedalttai/)
Catalan - [cubells](https://profiles.wordpress.org/cubells/)
Czech - [lordrak](https://profiles.wordpress.org/lordrak/)
Hungarian - [ilovewp.net](https://profiles.wordpress.org/ilovewp.net/)
Italian - [Lion73](https://profiles.wordpress.org/Lion73/)
Portuguese (Brazil) - [treedbox](https://profiles.wordpress.org/treedbox/)
Romanian - [Adrian Pop](https://profiles.wordpress.org/adrianpop/)
Russian - [ZAnatoly](https://profiles.wordpress.org/ZAnatoly/)
Ukrainian - [ZAnatoly](https://profiles.wordpress.org/ZAnatoly/)

= GADWP Translation Contributors =

For support and requests regarding plugin's localization [use this forum](https://wordpress.org/support/plugin/google-analytics-dashboard-for-wp). 

== License ==

Google Analytics Dashboard for WP it's released under the GPLv2, you can use it free of charge on your personal or commercial website.

== Changelog ==

= 4.8.4 =
- Bug Fix: add an unique class to jQuery UI Tooltips to avoid conflicts
- Bug Fix: multiple CSS improvements
- Enhancement: no more page re-loads on admin dashboard widget when switching between reports
- Enhancement: unified reporting system with real-time capabilities
- Enhancement: new tracking options enabling you to customize cookieName, cookieDomain, cookieExpires; props by [Martins Sipenko](https://github.com/martinssipenko) 
- Enhancement: display update notices only to admins
- Enhancement: force language packs updates for all available languages on a Network
- Enhancement: added View switch capabilities

= 4.8.3 =
- Enhancement: switching to translate.wordpress.org, you can find [more details here](https://deconf.com/moving-translations-to-wordpress-org/)

= 4.8.2.1 =
- Bug Fix: blank page on General Settings screen after failing to rebuild the bearer token
- Enhancement: Italian, Portuguese (Brazil), Hungarian, Arabic, Russian, English (Canada), Romanian translations updated
- Enhancement: new Localization section
- Enhancement: small UI updates

= 4.8.2 =
- Bug Fix: use only unique CSS selectors to avoid conflicts with other plugins
- Bug Fix: don't load unneeded CSS styles on frontend
- Bug Fix: switch to a new custom made cache system to avoid issues with broken transients
- Enhancement: rebuild and roll-back to a bearer token
- Enhancement: Greek translation updated

The full changelog is [available here](https://deconf.com/changelog-google-analytics-dashboard-for-wp/).