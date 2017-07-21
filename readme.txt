=== eMerchantPay Gateway Module for WooCommerce ===
Contributors: eMerchantPay
Tags: 1.2.2, 1.2.3, 1.3.0, 1.3.1, 1.3.2, 1.4.0, 1.5.0, 1.5.1, 1.5.2
Requires at least: 4.0
Tested up to: 4.8
Stable tag: 1.5.2
License: GPL-2.0
License URI: http://opensource.org/licenses/gpl-2.0.php

This Plugin for WooCommerce gives you the ability to process payments through eMerchantPay's Payment Gateway - Genesis.

== Description ==

*Requirements:*

2. WordPress 4.x (Tested up to 4.8)
2. WooCommerce 2.x or 3.x (Tested up to 3.0.9)
3. GenesisPHP 1.7.0

*Subscriptions:*
In order to process subscriptions, you need to purchase the [WooCommerce Subscription Extension](https://woocommerce.com/products/woocommerce-subscriptions/) (Tested up to 2.1.4).
Click [here](https://github.com/eMerchantPay/woocommerce-emp-plugin/tree/1.5.0#subscriptions) to learn more about setting up Subscription Module or
read our [Subscriptions Configuration wiki page](https://github.com/eMerchantPay/woocommerce-emp-plugin/wiki/WooCommerce-Subscription-Configurations).

*GenesisPHP Requirements:*

1. PHP version 5.5.9 or newer
2. PHP Extensions:

        * BCMath
        * CURL (required, only if you use the curl network interface)
        * Filter
        * Hash
        * XMLReader
        * XMLWriter

== Installation ==
1. Login into your **WordPress Admin Panel** with *Administrator privileges*
2. Navigate to **Plugins -> Add New**
3. Install through the Marketplace/ Select the downloaded **.zip** File
4. Activate the newly installed **WooCommerce eMerchantPay Payment Gateway Client** plugin
5. Navigate to **WooCommerce -> Settings -> Checkout**
6. Select your preferred payment method **eMerchantPay Checkout** or **eMerchantPay Direct**
6. Check **Enable**, set the correct credentials and click **Save changes**

== Changelog ==
= 1.5.2 =
* Subscription Extensions & fixes
    * Check sign-up fee for Subscription Products (Sign-up Fee required)
    * Cart validations

= 1.5.1 =
* Fix incorrect Billing Address Population for Gateway Request
 
= 1.5.0 =
* Added Support for PHP 7.1 and Remove Support for PHP < 5.5.9
* Update Genesis Client Library to 1.7.0
* Added new Transaction Types
    * Citadel
    * eZeeWallet
    * iDebit
    * INPay
    * InstaDebit
    * P24
    * PayPal Express
    * Mr.Cash
    * MyBank
    * Sepa Direct Debit
    * Trustly
* Added Better Handling of Module Requirements on Admin Page

= 1.4.0 =
* Added Support for Subscriptions

= 1.2.3 =
* Updated APM List
* Updated GenesisPHP library to v1.4.0

= 1.2.2 =
* Initial release.

= 1.3.0 =
* Added Direct (Hosted) Payment Method - Requires SSL to be enabled on the checkout pages
* Additional Module Settings
* Updated GenesisPHP library to v1.4.3

= 1.3.1 =
* Minor Issues have been resolved regarding Admin Backend Transactions (Capture, Refund, Void)
* Fixed minor Issue regarding Direct (Hosted) Payment Method Views 

= 1.3.2 =
* Minor Issues have been resolved regarding Capture Transaction and PHP 5.3 Support
