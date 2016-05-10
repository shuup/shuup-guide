Products
========

Adding Products
---------------

The Shoop Admin provides a simple interface for adding products to your
shop.

To navigate to the Products section of the Shoop Admin, open the Admin
menu and select the `Products` section under the `Products` category.

.. image:: products/products-menu.png

On the `Products` page, you will a list of all of the products currently
in your shop. In the upper right-hand corner, there is a button labelled
`New product`.

.. image:: products/new-product-button.png

New Product Form
~~~~~~~~~~~~~~~~

Clicking this will take you to the `new product form`, where you can enter
information about your new product.

.. image:: products/new-product-form.png

Like other Shoop Admin forms, required fields are marked with a red
asterisk and missing or invalid fields will be highlighted red on form
submission.

The left side of the form contains a number of sections of the form
(shown as tabs), and selecting a tab will present the different fields
and options for that section.

Base Product Tabs
^^^^^^^^^^^^^^^^^^

The top section of the form contains most of the basic product information
and settings.

General Information
    General information about the product, including product type, name,
    and product description.
Additional Details
    Miscellaneous information regarding the product, such as the product's
    stock and shipping mode, barcode information, and relevant keywords.
Accounting
    Bookkeeping-related information.
Physical Properties
    Physical dimensions and unit information for the product.
Manufacturer
    Selection choice for the product's manufacturer.

Shop-Specific Tabs
^^^^^^^^^^^^^^^^^^

Following the base product section are the following shop-specific tabs.
The names of these are preceeded by the relevant shop's name (initially
*Default*):

Visibility
    Front-end visibility settings for a specific shop.
Purchasing
    Pricing, supplier, and multiple-purchase settings.
Shipping & Payment
    Shipping and payment service-related settings (used to limit customer
    shipping and payment choices on checkout).

Media Tabs
^^^^^^^^^^^^^^^^^^

These sections are for managing the image and digital media content related
to the product.

Product Media
    Product-related file uploader and selector.
Product Images
    Product image uploader and selector.

.. tip::
   Advanced Product Media settings can be configured to deliver digital
   and downloadable content.

Customer Group Pricing Tab
^^^^^^^^^^^^^^^^^^^^^^^^^^

Pricing settings based on customer groups. If a customer belongs to
multiple groups, they will be presented the lowest price of the groups
to which they belong.

.. note::
   Customer Group pricing is currently not configurable for specific shops.

Saved Product Form
~~~~~~~~~~~~~~~~~~

Once the product has been successfully saved, additional options will be
available from the product edit form.

Attributes Tab
^^^^^^^^^^^^^^

See Attributes_.

Stock Management Tab
^^^^^^^^^^^^^^^^^^^^

For stocked product, this should display any stock-related management tasks,
depending on the product's supplier settings.

.. todo:: Add complete reference for product fields

Product Types
-------------

Product Types define classes products and are used to associate different
sets of attributes_ to a particular product, depending on its product type.

For example, a product of type *Book* might require specific information
such as author, ISBN, publisher, etc, while a product of type *Clothing*
might require size, color, or other custom attributes.

Attributes
----------

Shop owners can define their own attributes for product types from the
Attributes Admin.

1. Select the `Attributes` category from the Shoop Admin menu
2. Click the `New attribute` button in the upper right-hand corner
3. Enter a name and **unique** identifer for the attribute, and select
   the type, visibility mode, and searchability for the attribute
4. Select the `Product Type` page (under the `Products` category) from
   the Shoop Admin menu
5. Select the Product Type from the menu
6. Under the `Attributes` tab, check the box next to the attribute
   name for your new attribute.

.. tip::
   By default, new attributes are displayed on the product page, but there
   are multiple visibility options that can be selected form the Attributes
   edit page.

Cross-Selling
-------------

Package Products
----------------

Variation Products
------------------

Simple Variations
~~~~~~~~~~~~~~~~~

Variable Variations
~~~~~~~~~~~~~~~~~~~
