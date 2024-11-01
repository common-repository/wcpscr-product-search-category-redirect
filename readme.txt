=== Product Search Category Redirect ===
Contributors: ninetyninew
Tags: product search, search redirects, category redirects, product redirects, woocommerce search
Donate link: https://ko-fi.com/ninetyninew
Stable tag: 1.4.0
Tested up to: 6.6.1
License: GNU General Public License v3.0
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Redirects product searches that match a product category name to the product category page instead of showing the search results page.

== Description ==

With this extension when someone searches for products and their search terms match a product category then they will be redirected to that product category instead of the search results.

This is useful if you have products which do not contain the product category name in the title or description as those products wouldn't appear in search results when someone searches for the product category name.

= Features =

- Redirects search terms to product categories when matched
- Search term to category match can be in any order
- Lightweight and no configuration required

= Usage =

There are no settings to configure with this extension, once it is activated just try a product search for a product category and you will get redirected to that product category instead of seeing the search results.

For example, if you have a premium hoodies category then search for premium hoodies (or hoodies premium) and it will redirect you to the premium hoodies category instead of showing you the search results.

Note that the redirect will only work if you are using the standard WooCommerce product search which has URLs like this: `?s=search-term&post_type=product`.

= Donate =

If this product has helped you, please consider [making a donation](https://ko-fi.com/ninetyninew).

== Screenshots ==

1. Before activation, no results for hoodies as no products have titles or descriptions with hoodies included, only hoodie
2. After activation, redirects to the hoodies product category

== Frequently Asked Questions ==

= Nothing happened after activating? =

There are no settings to configure, see the usage section above to try out the redirects.

== Installation ==

Before using this product, please ensure you review and accept our [terms and conditions](https://99w.co.uk/#terms-conditions) and [privacy policy](https://99w.co.uk/#privacy-policy).

Before using this product on a production website you should thoroughly test it on a staging/development environment, including all aspects of your website and potential data volumes, even if not directly related to the functionality the product provides.

The same process should also be completed when updating any aspect of your website in future, such as performing installations/updates, making changes to any configuration, custom web development, etc.

Always refer to the changelog before updating.

= Installation =

Please see [this documentation](https://wordpress.org/support/article/managing-plugins/#installing-plugins-1).

= Updates =

Please see [this documentation](https://wordpress.org/documentation/article/manage-plugins/#updating-plugins).

= Minimum Requirements =

* PHP 7.4.0
* WooCommerce 8.5.0
* WordPress 6.3.0

= BETA Functionality =

We may occasionally include BETA functionality, this is highlighted with a `(BETA)` label. Functionality with this label should be used with caution and is only recommended to be tested on a staging/development environment. The functionality is included so users can test the functionality/provide feedback before it becomes stable, at which point the `(BETA)` label will be removed. Note that there may be occasions where BETA functionality is determined unsuitable for use and removed entirely.

= Caching =

If you are using any form of caching then it is recommended that the cache lifespan/expiry should be set to 10 hours or less. This is recommended by most major caching solutions to avoid potential issues with WordPress nonces.

= Screen Sizes =

- Frontend: Where elements may be displayed on the frontend they will fit within the screen width
- Backend: Where interfaces may be displayed it is recommended to use a desktop computer with a resolution of 1920x1080 or higher, for lower resolutions any interfaces will attempt to fit within the screen width but some elements may be close together and/or larger than the screen width

= Translation =

We generally recommend [Loco Translate](https://wordpress.org/plugins/loco-translate/) to translate and/or adapt text strings within this product.

= Works With =

Where we have explicitly stated this product works with another product, this should only be assumed accurate if you are using the version of the other product which was the latest at the time the latest version of this product was released. This is because, while usually unlikely, the other product may have changed functionality which effects this product.

== Changelog ==

= 1.4.0 - 2024-08-23 =

* Add: .pot to languages folder
* Add: Requires WooCommerce dependency header
* Update: PHP requires at least 7.4.0
* Update: WooCommerce requires at least 8.5.0
* Update: WooCommerce tested up to 9.2.2
* Update: WordPress requires at least 6.3.0
* Update: WordPress tested up to 6.6.1

= 1.3.3 - 2024-07-09 =

* Update: composer.json and composer.lock to woocommerce/woocommerce-sniffs 1.0.0
* Update: Installation and updates information in readme.txt
* Update: phpcs.xml codesniffs
* Update: WooCommerce tested up to 9.0.2
* Update: WordPress tested up to 6.5.5

= 1.3.2 - 2024-04-10 =

* Add: Translation information in readme.txt
* Update: WooCommerce tested up to 8.7.0
* Update: WordPress tested up to 6.5.2

= 1.3.1 - 2024-03-08 =

* Add: BETA functionality information to readme.txt
* Add: Caching information to readme.txt
* Add: Donation information to readme.txt
* Add: Works with information to readme.txt
* Update: Screen sizes information in readme.txt
* Update: WooCommerce tested up to 8.6.1
* Update: WordPress tested up to 6.4.3

= 1.3.0 - 2024-01-16 =

* Add: WooCommerce Cart/Checkout blocks compatibility
* Update: Changelog consistency

= 1.2.2 - 2023-12-18 =

* Update: Changelog keys
* Update: Code consistency
* Update: Development assets
* Update: PHP requires at least 7.3.0
* Update: WooCommerce requires at least 7.9.0
* Update: WooCommerce tested up to 8.4.0
* Update: WordPress requires at least 6.1.0
* Update: WordPress tested up to 6.4.2

= 1.2.1 - 2023-09-19 =

* Update: Header assets
* Update: WooCommerce tested up to 8.1.1
* Update: WordPress tested up to 6.3.1

= 1.2.0 - 2023-08-02 =

* Add: High Performance Order Storage (HPOS) compatibility if WooCommerce version is 8.0.0 or higher, note that this version includes several changes for HPOS compatibility, it is recommended you perform this update on a staging/development environment before updating the extension on a production website regardless of whether HPOS enabled, HPOS and the compatibility in this extension are very new, use with caution
* Update: Development assets
* Update: PHP requires at least 7.2.0
* Update: WooCommerce requires at least 7.3.0
* Update: WooCommerce tested up to 7.9.0
* Update: WordPress requires at least 5.9.0
* Update: WordPress tested up to 6.2.2

= 1.1.3 - 2022-12-23 =

* Update: Minor dashboard string changes
* Update: WooCommerce tested up to 7.2.2
* Update: WordPress tested up to 6.1.1

= 1.1.2 - 2022-10-21 =

* Update: Redirect now uses wp_safe_redirect
* Update: Code refactoring
* Update: PHP requires at least 7.0.0
* Update: WooCommerce requires at least 5.0.0
* Update: WordPress requires at least 5.4.0
* Update: WordPress tested up to 6.0.3

= 1.1.1 - 2022-04-23 =

* Update: Code refactoring
* Update: WordPress tested up to 5.9.3

= 1.1.0 - 2022-03-25 =

* Add: wcpscr_product_search_category_translation function
* Add: WooCommerce not installed/activated notice
* Update: WordPress tested up to 5.9.2
* Fix: Translations (if included in future) may not load due to load_plugin_textdomain not hooked on init

= 1.0.1 - 2021-05-27 =

* Add: Check for empty product categories before attempting redirect
* Update: Plugin headers and readme

= 1.0.0 - 2021-05-25 =

* New: Initial release