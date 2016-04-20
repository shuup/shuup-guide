Campaign management
===================

Shoop Ecommerce platform comes built in with customized and easily
extendable campaign management system. Shoop's modular campaign
management structure allows extending the feature to most innovative
campaign models and even integrations.

The campaigns are formed in the shop admin by building so called
"Campaign rules" by merchant. These rules can be merged together to
build varied complex campaigns targetted to different customers,
customer groups or for instance limiting the campaigns to products,
product groups or even use it as a pricing manager.

To manage campaigns in Shoop
----------------------------

1. Login into Shoop shop admin at https://youshopurl.com/sa
2. Open up the menu bar on top left hand side
3. Select `Campaigns` link
4. Choose which type of campaign to create, `Basket Campaigns`_, `Catalog
   Campaigns`_ or `Coupons`

Campaing types in brief
-----------------------

Basket campaing
    A campaign, that is offered or fullfilled in Shoop shopping
    basket. Can be for instance -5% discount, if visitor has 10 products
    in the shopping basket

Catalog campaign
    A campaign, that is configured to set certain products in the shop
    in discount

Coupons
    Create coupon codes to limit usage of a campaign only to a holder of
    a coupon code

Basket Campaigns
~~~~~~~~~~~~~~~~

Shoop campaign features is hooked up with something we call "basket
campaigns". Basically basket campaigns in Shoop are a campaign rules
check, that are validated in visitors shopping basket. These can be for
instance a discount percentage off of shopping basket total sum, if
certain conditions are met.

For instance the basket needs to contain one or more particular
products, to allows a discount of a certain sum.

.. tip::

   Try setting up a `Basket campaign` that is enabled if visitor basket
   has 10 or more products in the shopping

In `Campaigns / Basket campaigns`, on the top right hand side of the
shop admin interface you'll see a `Create new Basket Campaign` button.
Use this to create new basket campaigns. You can modify any of the
existing campaigns in the campaign table, by clicking on them.

Catalog Campaigns
~~~~~~~~~~~~~~~~~

Shoop comes built in with so called "catalog campaigns". Catalog
campaigns in Shoop are sort of a campaign rules check, that are
validated as soon as visitor arrives to the shop. These rules can be for
instance a discount of products.

.. tip::

   Try setting up a simple `Catalog campaign` with -5% discount off of
   certain products.

In `Campaigns / Catalog campaigns`, on the top right hand side of the
shop admin interface you'll see a `Create new Catalog Campaign`
button. Use this to create new basket campaigns. Modify any of the
existing campaigns (if any) in the campaign table, by clicking on them.

Campaign General Information
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Campaign `General Information` view is used to allow merchant to input
information of the campaign.

+------------+--------------------------------------------+-----------+
| Field      | Use                                        | Mandatory |
+============+============================================+===========+
| Name       | Name of the campaign (not visible on the   | Yes       |
|            | shop front-end)                            |           |
+------------+--------------------------------------------+-----------+
| Public name| Public name of the campaign to be          | Yes       |
|            | presented in the shop front-end, when the  |           |
|            | campaign name is displayed                 |           |
+------------+--------------------------------------------+-----------+
| Shop       | Shop selector for multi-shop setup.  Shop  | Yes       |
|            | where the campaign is active               |           |
+------------+--------------------------------------------+-----------+
| Start date | Setting start date for the campaign        | No        |
| and time   | using datepicker                           |           |
+------------+--------------------------------------------+-----------+
| End date   | Setting end date for the campaign using    | No        |
| and time   | datepicker                                 |           |
+------------+--------------------------------------------+-----------+
| Discount   | Set discount amount in %.  Either discount | No        |
| percentage | percentage or amount can be set.           |           |
+------------+--------------------------------------------+-----------+
| Discount   | Flat amount of discount.  Mutually         | No        |
| amount     | exclusive with percentage.  Either         |           |
|            | discount percentage or amount can be set.  |           |
+------------+--------------------------------------------+-----------+

Campaign rules
~~~~~~~~~~~~~~

Only after filling the campaign `General information`, you'll be able
to set up `Campaign rules`.

Each campaign can be configured individually. The following fields
determine when your campaign applies. You must select at least one rule
to be able to publish your campaign, but each of these rules are being
used simultaneously.

.. tip::

   Be careful not to build too complex campaigns for your visitors

.. note::

   Catalog and Basket campaigns come with different rule setups

Basket campaign rules
---------------------

The following fields determine when the campaign applies. You must
select atleast one rule to be able to save and run the campaign on your
shop

+---------------+----------------------------------------+-----------+
| Field         | Use                                    | Mandatory |
+===============+========================================+===========+
| Basket total  | Limit the campaign to match when       | No        |
| amount        | visitor has at least exactly, or over  |           |
|               | the set value worth of products in the |           |
|               | shopping basket.                       |           |
+---------------+----------------------------------------+-----------+
| Product count | Public name of the campaign to be      | No        |
| in basket     | presented in the shop front-end, when  |           |
|               | the campaign name is displayed         |           |
+---------------+----------------------------------------+-----------+
| Products      | Shop selector for multi-shop setup.    | No        |
|               | Shop where the campaign is active      |           |
+---------------+----------------------------------------+-----------+
| Coupon        | Setting start date for the campaign    | No        |
|               | using datepicker                       |           |
+---------------+----------------------------------------+-----------+

Catalog campaign rules
----------------------

The following fields determine when the campaign applies. You must
select atleast one rule to be able to save and run the campaign on your
shop

+------------+------------------------------------------+-----------+
| Field      | Use                                      | Mandatory |
+============+==========================================+===========+
| Product    | Limit the campaign to selected products  | No        |
+------------+------------------------------------------+-----------+
| Categories | Limit the campaign to products in        | No        |
|            | selected categories                      |           |
+------------+------------------------------------------+-----------+
| Contact    | Limit the campaign to members of the     | No        |
| Groups     | selected contact groups.                 |           |
+------------+------------------------------------------+-----------+
| Product    | Limit the campaign to selected product   | No        |
| Types      | types                                    |           |
+------------+------------------------------------------+-----------+
