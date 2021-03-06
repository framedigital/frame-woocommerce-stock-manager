=== WooCommerce Stock Manager ===
Contributors: Musilda
Donate link:
Tags: WooCommerce, stock manager
Requires at least: 3.5.1
Tested up to: 4.7
Stable tag: 1.1.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

WooCommerce Stock Manager allows you manage stock for products and their variables from one screen.

Plugin is compatible with WooCommerce 3.0+ and is tested on 3.0.7 version.
For older version WooCommerce use plugin 1.1.4

A few notes about the plugin:

*   You can set "Manage stock" for each product and variation
*   You can set "Stock status" for each product and variation
*   You can set "Backorders" for each product and variation
*   You can set "Stock" for each product and variation
*   You can set "Price" for each product and variation
*   You can set "Sale price" for each product and variation
*   You can set "Weight" for each product and variation

Stock field is green, when stock is more than 5 pieces.
Stock field is yellow, when stock is low than 5 pieces.
Stock field is red, when stock is 0 pieces.

You can filter products by type, category, stock manage or stock status.
You can sort products by name or sku.
Searching products by name or sku.

For better usabillity is possible hide some table cells.

Variants for variable product is posible edit after click on "Show variables" button.
Each product or variation, can be save separatelly, or you can save all displayed data.

Import/Export

With plugin is possible export all stock data from your eshop, edit them and import back with csv file.

Export file structure:

SKU - product unique identificator, required.
Manage stock - values: "yes", "notify", "no". If is empty "no" will be save.
Stock status - values: "instock", "outofstock". If is empty "outofstock" will be save.
Backorders - values: "yes", "notify", "no". If is empty "no" will be save.
Stock - quantity value.
Product type - type of product.
Parent SKU - if product is variant, parent product SKU is displayed for better filtering csv file.


== Installation ==

= Using The WordPress Dashboard =

1. Navigate to the 'Add New' in the plugins dashboard
2. Search for 'WooCommerce Stock Manager'
3. Click 'Install Now'
4. Activate the plugin on the Plugin dashboard

= Uploading in WordPress Dashboard =

1. Navigate to the 'Add New' in the plugins dashboard
2. Navigate to the 'Upload' area
3. Select `woocommerce-stock-manager.zip` from your computer
4. Click 'Install Now'
5. Activate the plugin in the Plugin dashboard

= Using FTP =

1. Download `woocommerce-stock-manager.zip`
2. Extract the `woocommerce-stock-manager` directory to your computer
3. Upload the `woocommerce-stock-manager` directory to the `/wp-content/plugins/` directory
4. Activate the plugin in the Plugin dashboard


== Frequently Asked Questions ==

Q: I see white screen, when i click on Export button.
A: Try increase memory limit.

Q: Quantity change not working.
A: Be sure, that you have active stock manage.

== Screenshots ==

1. Edit stock product data
2. Edit stock variations data
3. Import/export
4. Show product variations

== Changelog ==

= 1.1.5 =
* WooCommerce 3.0+ compatibility
* Sku edit is now via onclick function
* Fix Sku display issue
* French translations

= 1.1.4 =
* Fixed Save all button issue

= 1.1.3 =
* Typo admin fix

= 1.1.2 =
* Added input for sku change
* Use $product->set_stock for set qty value
* Added searching products by product name
* Wildcard for searching by sku
* Product name edit directly in table - green pen icon
* Added sale price
* Availability switch off/on table cells - price, sale price, weight, manage stock, stock status, backorders, stock
* New setting for cells displaying
* Fixed save all price error

= 1.1.1 =
* Fixed Search by SKU issue
* Improve filter for multiple values
* Added Order by filter
* Added Persian translation

= 1.1.0 =
* Removed "f" typo on admin page
* Fixed not saving issue
* Added product id paramater into hooks
* Optimized pagination method
* Fixed on sae price issue

= 1.0.9 =
* Fixed wrong generate AJAX nonce
* User manage WooCommerce capability control in stock_manager_save_one_product_stock_data

= 1.0.8 =
* Fixed security vulnerabily in AJAX call

= 1.0.7 =
* Fixed price saving
* New hook stock_manager_table_th in table head before Save text
* New hook stock_manager_table_simple_td in table line before Save button - simple product
* New hook stock_manager_table_variation_td in table line before Save button - product variation
* Edit product weight
* Added product name into export file

= 1.0.6 =
* Fixed issue with export class

= 1.0.5 =
* Search product by sku
* Edit product regular price
* Link to product edit page

= 1.0.4 =
* Fix error on attribut label displaying

= 1.0.3 =
* Added toggle display for variations
* Variation have their attributes as "variation name"
* Added availability work with plugin setting, for shop managers
* Fix displaing zero, when stock is low then 0

= 1.0.2 =
Fix wrong table displaing in administraion in FF and IE
Added Spanish translate - thanks to Miguel Acosta
Added Slovakia translate - thanks to Tomas Kusenda

= 1.0.1 =
Fix product filter issue

= 1.0.0 =
Startup version


== Upgrade Notice ==

= 1.0.7 =
* Fixed price saving
* New hook stock_manager_table_th in table head before Save text
* New hook stock_manager_table_simple_td in table line before Save button - simple product
* New hook stock_manager_table_variation_td in table line before Save button - product variation
* Edit product weight
* Added product name into export file

= 1.0.6 =
* Fixed issue with export class

= 1.0.5 =
* Search product by sku
* Edit product regular price
* Link to product edit page

= 1.0.4 =
* Fix error on attribut label displaying

= 1.0.3 =
* Added toggle display for variations
* Variation have their attributes as "variation name"
* Added availability work with plugin setting, for shop managers
* Fix displaing zero, when stock is low then 0

= 1.0.2 =
Fix wrong table displaing in administraion in FF and IE
Added Spanish translate - thanks to Miguel Acosta
Added Slovakia translate - thanks to Tomas Kusenda

= 1.0.1 =
Fix product filter issue

= 1.0.0 =
Startup version