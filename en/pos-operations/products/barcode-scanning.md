---
title: Barcode Scanning
description: WooCommerce POS is able to filter products by the SKU field, this allows you to instantly add products to cart using a barcode scanner.
tags: barcode, barcode-scanning, filtering, search, sku, sku-field
---

### Barcode scanning overview

WooCommerce POS allows to quickly add Products to the Cart by using the special Barcode scanning mode. This mode can be activated by either clicking on the icon next to the search field or by [using the appropriate HotKey](/hotkeys.md).

![Search Scan Barcode modes](http://wcpos.com/wp-content/uploads/2014/07/search-scan-mode.png)

### Custom Barcode field
By default WooCommerce POS will use the _SKU_ field of a Product as barcode meta field but this can be changed in the [Products Settings Panel](/settings/custom-barcode-field.md) or programatically by using the `woocommerce_pos_barcode_meta_key` filter. 


![By default WooCommerce POS will use the SKU field as the barcode. ](http://wcpos.com/wp-content/uploads/2016/06/product-sku.png "By default WooCommerce POS will use the SKU field as the barcode")

[WooCommerce POS Pro](http://wcpos.com/pro) users can use any product meta field by selecting a Barcode Field in `WP Admin > POS > Settings > General`

![Select custom barcode field in WooCommerce POS Pro](http://wcpos.com/wp-content/uploads/2016/06/select-custom-barcode-field.png "Select custom barcode field in WooCommerce POS Pro")

{% gist id="kilbot/88cbd3ac5613eca90eea" %}{% endgist %}

{% hint style='info' %}
A barcode must be unique for each product.
{% endhint %}



The following features are being planned for future releases:

*   Barcode scanning using mobile device camera. This will require a native WooCommerce POS app to gain access to the device hardware. Native apps are on the wish list but adding features to the web version is the highest priority at the moment.
*   Hot key activation

