=== Connector for WooCommerce and Zoho CRM ===
Contributors: aspengrovestudios, annaqq
Tags: woocommerce, zoho crm, zoho, crm, customer relationship management, ecommerce, e-commerce, integration
Requires at least: 3.5
Tested up to: 6.6.1
Stable tag: 1.1.3
License: GPLv3 or later
License URI: https://www.gnu.org/licenses/gpl-3.0.en.html

Automatically add WooCommerce customers as contacts and/or leads in Zoho CRM.

== Description ==

The Connector for WooCommerce and Zoho CRM plugin automatically adds the customer as a contact and/or lead in your Zoho CRM account whenever an order is placed in WooCommerce.

As of v1.1.0, this plugin **supports Zoho CRM API version 2**. Users updating the plugin from v1.0.9 or earlier will need to re-authenticate their Zoho CRM account on this plugin's settings page.

Features:

* Add customers as contacts and/or leads in Zoho CRM when they place an order in your WooCommerce store.
* Optionally update contacts and/or leads for customers with existing records in Zoho CRM.

A [pro version](https://wpzone.co/product/woocommerce-and-zoho-crm-connector-pro/?utm_source=connector-for-woocommerce-and-zoho-crm&utm_medium=link&utm_campaign=wp-repo-upgrade-link) with the following additional features is also available:

* Add order details (product names and quantities) as a note to the contact and/or lead corresponding to the customer.
* Create a potential based on the order and linked to the customer’s contact record (if one was found or created).
* Manually send individual orders to Zoho CRM from the Order Actions menu on the Edit Order page.
* Manually send orders to Zoho CRM individually or in bulk from the order list.

Requirements:
* cURL: The plugin uses the cURL library to perform HTTP requests to the Zoho CRM API. Make sure that cURL is installed and enabled on your server. Without cURL, the plugin will not function correctly.

If you like this plugin, please consider leaving a comment or review.

## You may also like these plugins
[WP Zone](https://wpzone.co/) has built a bunch of plugins, add-ons, and themes. Check out other favorites here on the repository and don’t forget to leave a 5-star review to help others in the community decide.

* [Product Sales Report for WooCommerce](https://wordpress.org/plugins/product-sales-report-for-woocommerce/) - setup a custom sales report for the products in your WooCommerce store with toggle sorting options. Including or excluding items based on date range, sale status, product category and id, define display order, choose what fields to include, and generate your report with a click.
* [Export Order Items for WooCommerce](https://wordpress.org/plugins/export-order-items-for-woocommerce/) - export the order details for each sale in your WooCommerce store. Simplify order fulfillment, generate accounting reports in a few clicks, and download into CSV format for readability and universal compatibility with Export Order Items.
* [Replace Image](https://wordpress.org/plugins/replace-image/) – keep the same URL when uploading to the WordPress media library
* [Force Update Check for Plugins and Themes](https://wordpress.org/plugins/force-update-check-for-plugins-and-themes/) -force Update Check for Plugins and Themes forces WordPress to run a theme and plugin update check whenever you visit the WordPress updates page
* [Connect SendGrid for Emails](https://wordpress.org/plugins/connect-sendgrid-for-emails/) -  connect SendGrid for Emails is a third-party fork of (and a drop-in replacement for) the official SendGrid plugin
* [Custom CSS and JavaScript](https://wordpress.org/plugins/custom-css-and-javascript/) - allows you to add custom site-wide CSS styles and JavaScript code to your WordPress site. Useful for overriding your theme’s styles and adding client-side functionality.
* [Disable User Registration Notification Emails](https://wordpress.org/plugins/disable-user-registration-notification-emails/) - when this plugin is activated, it disables the notification sent to the admin email when a new user account is registered.
* [Inline Image Upload for BBPress](https://wordpress.org/plugins/image-upload-for-bbpress/) - enables the TinyMCE WYSIWYG editor for BBPress forum topics and replies and adds a button to the editor’s “Insert/edit image” dialog that allows forum users to upload images from their computer and insert them inline into their posts.
* [Password Strength for WooCommerce](https://wordpress.org/plugins/password-strength-for-woocommerce/) - disables password strength enforcement in WooCommerce.
* [Potent Donations for WooCommerce](https://wordpress.org/plugins/donations-for-woocommerce/) – acceptance donations through your WooCommerce store
* [Shortcodes for Divi](https://wordpress.org/plugins/shortcodes-for-divi/) - allows to use Divi Library layouts as shortcodes everywhere where text comes.
* [Stock Export and Import for WooCommerce](https://wordpress.org/plugins/stock-export-and-import-for-woocommerce/) - generates reports on the stock status (in stock / out of stock) and quantity of individual WooCommerce products.
* [Random Quiz Generator for LifterLMS](https://wordpress.org/plugins/random-quiz-addon-for-lifterlms/) - pull a random set of questions from your quiz so users never get the same question twice when retaking or setting up a practice quiz.
* [WP and Divi Icons](https://wordpress.org/plugins/wp-and-divi-icons/) - adds over 660 custom outline SVG icons to your website. SVG icons are vector icons, so they are sharp and look good on any screen at any size.
* [WP Layouts](https://wordpress.org/plugins/wp-layouts/) - the best way to organize, import, and export your layouts, especially if you have multiple websites.
* [WP Squish](https://wordpress.org/plugins/wp-squish/) - reduce the amount of storage space consumed by your WordPress installation through the application of user-definable JPEG compression levels and image resolution limits to uploaded images.

To view WP Zone's premium WordPress plugins and themes, visit our [WordPress products catalog page](https://wpzone.co/product/)

== Installation ==

1. Click "Plugins" > "Add New" in the WordPress admin menu.
2. Search for "Connector for WooCommerce and Zoho CRM".
3. Click "Install Now".
4. Click "Activate Plugin".

Alternatively, you can manually upload the plugin to your wp-content/plugins directory.

== Frequently Asked Questions ==

###  **How to Check if cURL is Installed ?**
To check if cURL is installed on your server, log in to your WordPress admin dashboard and navigate to Tools > Site Health. Once there, click on the Info tab and scroll down to the Server section. Look for "cURL" in the list of server details. If cURL is listed and shows as enabled, your server is ready to use the plugin. If you do not see cURL listed or it appears as disabled, you will need to contact your hosting provider to have it installed or enabled.


== Changelog ==

= 1.1.3 =
* Declare HPOS compatibility
* Remove outdated admin notice about Zoho CRM API v1

= 1.1.2 =
* Plugin rebranded

= 1.1.1 =
* Fixed compatibility with regional Zoho datacenters (zoho.com.cn, zoho.eu, zoho.in, zoho.com.au)

= 1.1.0 =
* Switched to Zoho CRM API version 2

= 1.0.8 =
* Added notice about API version 2
* License is now GPLv3+

= 1.0.7 =
* Added Zoho CRM URL setting

= 1.0.6 =
* Fixed issue with long site titles preventing authentication

= 1.0.5 =
* Fixed bug with ampersand in field values

= 1.0.2 =
* Fixed bug with non-alphanumeric characters in blog names
* Added option to disconnect Zoho CRM account

= 1.0 =
* Initial release

== Upgrade Notice ==

= 1.1.0 =
This plugin now supports Zoho CRM API version 2; please update by December 31, 2019 when API version 1 will be sunset. You will need to re-authenticate your Zoho CRM account under WooCommerce > Zoho CRM Integration after installing this update.
