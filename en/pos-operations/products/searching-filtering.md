---
title: Product Searching and Filtering
description: You can use search phrases to filter products by any attribute such as id, category and type.
tags: categories, category, filtering, product-tabs, searching
---

With WooCommerce POS you can search for product by name and also filter the list by certain attributes:


### Searching by Product Name/Title
A search by name is performed by beginning to type a products' name in the search field.

![](http://wcpos.com/wp-content/uploads/2014/08/free-text-e1409502417821.png)

### Filtering the Products list
Filters are applied by either typing the filter name followed by a colon and the value to filter by or by setting up a custom filter tab in the Products Settings section in the POS Administration.

#### Manual filtering

Below is a table of the current available filter and their possible values.

Filter by | Filter name | Possible filter values | Example
--------- | ----------- | ---------------------- | -------
Category | `category` | the product's category slug | `category:music`
Sku | `sku` | the product sku | `sku:music`
Product Type (Simple or Variable) | `category` | the product category slug | `category:music`
Downloadable | `downloadable` | `true` or `false`  | `downloadable:true`
Virtual | `virtual` | `true` or `false`  | `virtual:false`
In Stock | `in_stock` | `true` or `false`  | `in_stock:true`
Back Ordered | `backordered` | `true` or `false`  | `backordered:false`
Featured | `featured` | `true` or `false`  | `featured:true`
On Sale | `on_sale` | `true` or `false`  | `on_sale:true`

**Tips:**
- You can _combine a name search with a filter_ for more accuracy. Example: Search all Products from the _Music_ category which name contains '_Woo_': `cat:music Woo`. 
- You can also _add multiple filters_ to search on multiple attributes. Example: Search for Products from the _Clothing_ category which are _On Sale_ and which name begins with _Hood_: `cat:clothing on_sale:true Hood`.
- If you wanted to select the Movie Posters category you could use `cat:"movie posters"`.

#### Custom filter tabs

The WooCommerce POS allows you to setup custom filter tabs. This is done wia the Products Settings panel in the POS Administration section: `WP Admin > POS > Settings > Products`.

You can add as many tabs as you like giving each of them a Label and a filter. The filters have the forl of the filters available in the Manual filtering section.

![Setting up Custom Filters Tabs](https://s3.amazonaws.com/wcpos/screenshots/Settings__Localhost__WordPress_2016-12-18_23-27-54.png)

![Custom Filters Tabs in the POS](https://s3.amazonaws.com/wcpos/screenshots/Point_of_Sale_-_Localhost_2016-12-18_23-30-03.png)


