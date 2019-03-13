
Stock Management
================

Shuup comes with built in stock management system. The stock management isn't
activated in shop admin by default, but the activation can be done by merchant
in a few easy steps. The Stock management setup process is guided process in
the Shuup shop admin.

Since all products aren't always stocked (like downloadable products) a good
thing to keep in mind is, that to be able to manage product stock, a product
must be first set as `Stocked`. Also to have a stock, it's required to have at
least one `Supplier`. Stock can be easily managed in Shuup shop admin through
any of the Stocked products, or in dedicated **Products / Stock management**
view.


Activating Stock management
---------------------------

**Set supplier stock managed:**

1. Login into Shuup shop admin at `https://youshopurl.com/sa`
2. Open up the menu bar on top left hand side
3. Select **Products / Suppliers** and open up `Simple supplier`-module
   from Suppliers -table
4. Check on **Stock Managed** and **Save**

.. tip::

    Shuup is prepared to use several supplier modules and each of them can
    have their own stock

Set product as stocked
----------------------

Next, let Shuup know, which of your products are actually stocked. Decide
which products stock you want to manage. Find these product in
**Products / Products**

Open up the product you want to manage and check that the product has it's
stock managed at **Additional details**. Set the option `stock` as **Stocked**.

.. tip::

    This will activate Stock Management for the product.
    From now on the stock of this particular product can be managed in
    `Stock management`_

Managing stock
--------------

Managing stock in Shuup is simply clean. Stock managing is available through
each specific product at `Products` or at it's own `Stock management`-views
in shop admin.

Whether the merchant needs to manage only one product, or several product
stocks at a time, in both of the use case variations the stock management
behaviour is the same. The only difference is, that in Stock Management view
a merchant may easily view all the products at one glimpse and manage their
stocks. In product settings view the stock is managed only for one particular
product.

This way the stock management is easy whether merchant is browsing for
a single product and has a sudden need to manage it's stock, or adding
various products to the stock at once.

.. tip::

    When adding stock, it's good to notice, that merchant should always
    include information of product purchase price in shop currency, and the
    quantity to add to the stocks. These will affect in stock reports.


How to manage stock on a product
--------------------------------

1. Decide which products stock you want to manage, find the product in
   **Products**
2. Open up the product and scroll down for **Stock management** tab

.. tip::

    Before trying to manage stock on a product make sure, that the Supplier
    and product has stock setting set as **Stocked**

**Add stock:** Input your product purchase price and quantity and select
**Add stock**
**Remove stock:** Input a negative value of how many products you want to
remove, input product purchase price and quantity and select **Remove stock**

.. tip::

    Your stock physical count, logical count, value per unit and total value
    is automatically updated after each time you add or remove stock


How to manage stocks in general
-------------------------------

1. Navigate to `Stock Management` in shop admin, through the menu
   **Products / Stock management**
2. Locate the product you want to manage the stock for

.. tip::

    Before trying to manage stock on a product make sure, that the Supplier
    and product has stock setting set as **Stocked**

**Add stock:** Input your product purchase price and quantity and select
**Add stock**
**Remove stock:** Input a negative value of how many products you want to
remove, input product purchase price and quantity and select **Remove stock**

.. tip::

    Your stock physical count, logical count, value per unit and total value
    is automatically updated after each time you add or remove stock
