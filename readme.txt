=== WC API Custom Meta ===
Contributors: judgej
Tags: woocommerce, api
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=B4STZL8F5WHK6
Requires at least: 4.0.0
Tested up to: 4.7.5
Stable tag: 0.7.1
License: GPL2
License URI: http://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html

Allows access to custom meta fields on products through the API.

== Description ==
Allows access to custom meta fields on products through the API.
In short, installing this plugin on your WooCommerce site, will extend the
WooCommerce API so that custom metadata can be passed back and forth through
that API.

See the main documentation here: https://github.com/judgej/wc-api-custom-meta

== Installation ==
Standard installation - whatever you normally do.

Will only work with WooCommerce with the *legacy* V2 API at his time, which means any version
from mid-2015, until the V2 API is eventually removed. It may work with the *legacy* V3
API, but that has not been tested.

PLEASE NOTE: the V2 REST API now supports metadata out of the box. This is available in WC 3.x
For this reason, this plugin will no longer be supported for WC 3.x onwards - it no longer has
a purpose. More details on how to move to the new API are given on the git repository:
https://github.com/judgej/wc-api-custom-meta

== Changelog ==

= 0.7.1 =
* Fix for issue https://github.com/judgej/wc-api-custom-meta/issues/22
