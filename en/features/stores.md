---
title: Stores
description:  
tags: 
---

**WooCommerce POS Pro adds the ability to create *separate stores* for your physical sales.** 

{% hint style='info' %}
This feature is requires an upgrade to [WooCommerce POS Pro](http://wcpos.com/pro).
{% endhint %}


![Example of stores list](http://wcpos.com/wp-content/uploads/2016/08/stores-page.png "Example of stores list")


Stores can have their *own address, logo and other details* for use on the [receipt template](receipts.html). 
Stores can use *different tax rates* and *Sales can be separated by store for [reporting](reports.html#sales-by-store)*.

![Example of store edit page](http://wcpos.com/wp-content/uploads/2016/08/edit-store-page.png "Example of store edit page")

### Assign Cashiers to Stores

...

### Opening Hours Widget

Each Store you setup comes with the ability to set and display its Opening Hours in a Widget on your site.

Hours Setup | Widget Setup | Site display
----------- | ------------ | ------------
![](https://s3.amazonaws.com/wcpos/screenshots/Edit_Store__Localhost__WordPress_2016-12-18_19-20-22.png) | ![](https://s3.amazonaws.com/wcpos/screenshots/Widgets__Localhost__WordPress_2016-12-18_19-19-13.png) | ![](https://s3.amazonaws.com/wcpos/screenshots/Localhost__Just_another_WordPress_site_2016-12-18_19-17-48.png)

### Multi Inventory

{% hint style='info' %}
Multi-inventory is not currently a feature of the Pro plugin. 
The following information is intended to assist users until WooCommerce POS Pro officially supports multi-inventory.
{% endhint %}

Multi-inventory stores is one of the most requested features for WooCommerce POS Pro. 
This feature would allow stores owners to assign products to different stores and manage the stock between each physical store and the online store. 

Creating multi-inventory functionality is a non-trivial task. 
There are a couple of plugins already working on the problem, such as [WooCommerce Warehouses](https://codecanyon.net/item/woocommerce-warehouses/13087646) and [WooCommerce MultiStore](http://woomultistore.com/).
Currently it makes sense to focus development on other core POS features and integrate with one of these plugins once they mature to stable solutions.

In the short term, you may be able to meet most of your requirements using the [WordPress MultiSite feature](https://codex.wordpress.org/Create_A_Network). 
By creating a site for each store, you can then install WooCommerce and WooCommerce POS on each site, keeping each store inventory completely separate. 
WooCommerce Multisite (mentioned above) uses this approach with an added layer to manage inventory between sites.