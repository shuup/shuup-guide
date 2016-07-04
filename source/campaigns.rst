Campaigns
=========

Shoop Ecommerce platform comes built in with customized and easily
extendable campaign management system. Shoop's modular campaign
management structure allows extending the feature to most innovative
campaign models and even integrations.

Campaign Types
--------------

Shoop has two different types of campaigns:

Basket Campaign
    A campaign that is offered or fulfilled in Shoop shopping
    basket. For example, a customer may be given a 5% discount off
    their total order if their basket contains at least 10 products.

Catalog Campaign
    A campaign that is offered shop-wide based on the customer,
    product, product type, or other such conditions.

Creating a Campaign
-------------------

1. Navigate to either the `Basket Campaigns` or `Catalog Campaigns`
   admin page by clicking `Basket Campaigns` or `Catalog Campaigns`
   under the `Campaigns` category from the Shoop Admin menu.

.. image:: campaigns/basket-campaigns-menu.png

2. Click either the `Create a new Basket Campaign` or `Create a new
   Catalog Campaign` button in the admin page toolbar.

.. image:: campaigns/create-new-basket-campaign-button.png

3. Enter general information regarding the campaign, such as the name,
   public name, basket line text, start/end dates, and any coupons to
   be associated with the campaign.

   .. image:: campaigns/campaign-general-information.png

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

   .. note:: If no start date is provided, it will take effect
             immediately.

             If no campaign end date is provided, the campaign
             will stay in effect indefinitely.

4. Click `Save` to create the campaign. Once a campaign has been saved,
   rules and effects can be added to define its behavior.

.. tip::

   Try setting up a cross-selling basket campaign by offering a
   discount on one product when a customer purchases  a related product.

.. tip::

   Try setting up a simple catalog campaign with a 5% discount for a
   particular product.

Rules and Effects
-----------------

Whether or not a campaign be applied to a particular order and how it
will be applied depends on its *Rules* and *Effects*.

Rules
    The conditions or criteria that an order must meet before a
    campaign will be applied. These may include having a basket with
    a certain total value (for a basket campaign) or requiring the
    customer to belong to a specific customer group (for a catalog
    campaign). Different rules will be available depending on whether
    they are being applied to a basket campaign or a catalog campaign.

Effects
    If a customer's order meets the requirements of all of the
    campaign's rules, any enabled effects will be applied to their
    order. These are usually discounts applied to the order, such as
    discounts on the total basket value, discounted or free quantities
    of a particular product, or other various types of discounts.

Coupons
    Used to limit usage of a basket campaign to only holders of a valid
    coupon code.

Adding Rules and Effects
~~~~~~~~~~~~~~~~~~~~~~~~

Once a campaign has been created, Rules and Effects can be added from
the campaign's admin page.

To add rules and effects:

1. Click either the `Rules` or `Effects` tab on the left hand side of
   the screen.

   .. image:: campaigns/rules-tab.png

2. Select the rule or effect type from the dropdown menu and click
   either the `Add rule` or `Add effect` button below to add a new
   rule or effect form.

   .. image:: campaigns/add-rule-button.png

3. Enter any required values in the rule or effect form, and click
   `Save` to attach the rules or effects to the campaign.

   .. image:: campaigns/rule-form.png

Basket Rules
~~~~~~~~~~~~

The following rules are available to basket campaigns:

Basket product count
    Limit to baskets containing at least the specific number of products
Basket maximum product count
    Limit to baskets containing at most the specific number of products
Basket total value
    Limit to baskets containing at least the specified total amount
Basket maximum total value
    Limit to baskets containing at most the specified total amount
Products in basket
    Limit to baskets containing a certain quantity of the selected product(s)

    .. note::

       This rule applies if a basket contains *any* of the selected
       products (i.e., a certain number of product A *or* a certain
       number of product B).

       In order to require product A *and* product B, create a separate
       rule for product A and product B.

Contact Group
    Limit to customers belonging to a specific contact group
Contact
    Limit to selected customer contacts

Catalog Rules
~~~~~~~~~~~~~

Contact
    Limit to seleclted customer contacts
Contact Group
    Limit to customers belonging to a specific contact group
Product
    Limit to a specific product
Product Category
    Limit to products belonging to a specific category
Product Type
    Limit to products of a specific type

Basket Effects
~~~~~~~~~~~~~~

Campaign Effects
~~~~~~~~~~~~~~~~

Creating a Coupon Code
----------------------

1. Navigate to the `Coupons` admin page by clicking `Coupons` under
   the `Campaigns` category from the Shoop Admin menu.

.. image:: campaigns/coupons-menu.png

2. Click `Create new Coupon` button in the admin page toolbar.

.. image:: campaigns/create-new-coupon-button.png

3. Either type the desired coupon code you want your customers to enter,
   or click the `Generate` button to randomly generate a coupon code.

.. image:: campaigns/generate-coupon-button.png

4. Enter general information regarding the coupon, such as the usage
   limit per customer and the over usage limit (or total number of
   redeemable coupon codes).

.. image:: campaigns/coupon-general-information.png

.. tip::

   As coupon codes are redeemed through the store, the total number
   of used coupon codes will be visible through the coupon's admin
   page.
