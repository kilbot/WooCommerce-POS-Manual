---
title: The POS features
description: The POS allows to seach and filter products to add them to a Customer's Cart and then proceed Checkout.
tags: product display
---

The main feature of the WooCommerce POS Plugin is to allow to take orders from a physical Point of Sale.

A Cashier will typically add Products from the list to the Cart and proceed to Checkout once the Customer is ready to pay.

The POS features are:
- [Manually Search & Filter Products to be added to the Cart](#manually-searching-and-filtering-products)
- [Use a barcode scanner to automatically add matching product to the Cart](#barcode-scanning)
- Edit the Cart Items
- Add Fees and Shipping Fees Orders
- Add Notes to Orders
- [Assign a Customer to Orders](#assign-a-customer-to-orders)

![The POS Screen](https://s3.amazonaws.com/wcpos/screenshots/Point_of_Sale_-_Localhost_2016-12-18_12-44-17.png)

### Manually Searching and Filtering Products

The POS interface allows you to easily search Products through your Catalog by:

- Searching Products by name
- Filtering the Products list by certain attributes (Category, Sku, In Stock ...)

See _[Searching & Filtering](/pos-operations/products/searching-filtering.md)_ in the POS operating manual.

### Barcode scanning
WooCommerce POS allows to instantly add a Product (or a Product Variation) to the Cart by using any Product's custom field and its special Barcode Scanning mode.

To see this feature in action please go to http://demo.wcpos.com/pos/ 
Type (or copy & paste) `BARCODE` and an item will be added to the cart.
Type (or copy & paste) `VARIATION1` and a variation will be added to the cart.

See _[Using the Barcode Scanning Mode](/pos-operations/products/barcode-scanning.md)_ in the POS operating manual.

### Edit the Cart Items

After an Item has been added to the Cart the Cashier can:
- Remove it from the Cart
- Modify the quantity of items
- Alter the price
- Change the Tax Rate
- Add additional information per items

See _[Using the Cart](/pos-operations/cart/_cart_.md)_ in the POS operating manual.

### Add Fees and Shipping Fees Orders

For each Order the Cashier can:
- [Add Fees and choose the Fees Tax Rate](/pos-operations/cart/fees.md)
- [Add Shipping costs and choose the Shipping Tax Rate](/pos-operations/cart/shipping.md)

### Add Notes to Orders

Each Order can be annotated. See [Add a note to the Order](/pos-operations/cart/note.md) in the POS operating manual.

### Assign a Customer to Orders

WooCommerce POS allows a Cashier to easily associate an existing Customer to an Order at Checkout. Pro Users can also create a Customer on-the-fly with just an email.

See _[Associating a Customer to an Order](/pos-operations/cart/customers.md)_ in the POS operating manual.


