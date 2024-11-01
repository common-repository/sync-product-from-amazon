=== Sync Product From Amazon ===
Plugin Name: Sync Product From Amazon
Plugin URI: sync-product-from-amazon
Author: Multidots
Author URI: https://www.multidots.com/
Contributors: multidots
Tags: amazon, product
Requires at least: 6.2
Stable tag: 1.0
Tested up to: 6.6.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
This plugin will be used to retrieve various Amazon product details.

== Description ==
If you want to display products from your Amazon store on WordPress posts or pages, this plugin is perfect for you. It fetches product details from Amazon and allows you to save them into posts or pages with ease.
The plugin supports both shortcodes and Gutenberg blocks to display products on the frontend. All you need is the product's ASIN number, which you can find on the Amazon product page.
Additionally, this plugin allows you to create individual posts or pages to showcase Amazon products. You can either add products manually or import multiple products in bulk using their ASIN numbers.

## Features:
* **Amazon Region & API Keys:** The plugin sends requests to Amazon's Product Advertising API based on the target locale's AWS region. You need to provide API Access Key, Secret Key, and Partner Tag from your Amazon Associates account.
* **Shortcode Support:** Use the `[sync_product_from_amazon asin="asin_number"]` shortcode to display Amazon product details in a post or page. To show multiple products, add ASIN numbers separated by commas.
* **Gutenberg Block**: A dedicated Sync Product From Amazon block fetches and displays product details using the ASIN number within the Gutenberg editor.
* **Caching:** Product data is cached for **24 hours** to reduce API calls, and the cache clears automatically after this period. A manual cache clearing option is also available.
* **Bulk Import:** The plugin allows importing multiple Amazon products **(up to 10 ASINs)** into any post or page. You can specify post type and status during the import process.
* **Manual Import:** You can manually add a product to a post or page using Amazon Product's ASIN number. Simply enter the ASIN, and the plugin will fetch the product details for you. You can also specify the post type and post status during this process.

== Installation ==
1. Upload `sync-product-from-amazon` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Enter Amazon's Product Advertising API credentials and it is ready to use.

== Frequently Asked Questions ==
= Do I need API to work with this plugin? =
Yes, you will need Product Advertising API 5.0 account and their credentials to work with this plugin. Here is the link of the API. https://webservices.amazon.in/paapi5/documentation/
= Where can I get the ASIN Numbers of Amazon Product? =
You can get the ASIN Numbers of Amazon Product from the product's page itself. Either from the URL and the Product information.
= Is this a free plugin? =
Yes, this is a free plugin.

== Screenshots ==
1.
2.
3.
4.
5.
6.

== Changelog ==
= 1.0 =
* Initial plugin version.