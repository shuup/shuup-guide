Multivendor
===========

.. note:: The Multivendor feature is currently only available through a license.
    For more information, contact support@shuup.com 

The Multivendor Addon enables multiple features that facilitate the management 
of a multivendor marketplace. The marketplace owner can manage several Vendors 
more easily while vendors can select the products they want to sell, their 
prices as well as manage their stocks.

User-roles and Permissions
~~~~~~~~~~~~~~~~~~~~~~~~~~

Permissions is the basic and Initial configuration all modern application 
should have. They are created to restrict features to a certain group of users. 
Shuup restrict the features using `Permission Groups`. A user can be linked to 
many permission groups. As the permissions must be explicitly granted (you must 
check what features are allowed to access), a user will accumulate all the 
permissions from all the linked permission groups. 

Common user roles for multivendor:

- Admin: (superuser). Superusers has all the permissions and can see all admin 
  modules available.
- Staff: Can see admin modules defined for the staff group. Main role is to 
  manage vendors, products and orders.
- Vendor: Can manage own products and manage vendor order lines, see vendor 
  reports.

These roles are already created in multivendor environment and can be tweaked 
to meet the project requirements.

As a Vendor
~~~~~~~~~~~

Vendor Registration
^^^^^^^^^^^^^^^^^^^

1. From the marketplace home page, navigate to `/v/register` to access the 
   registration form. 

2. Fill out the Vendor information part with the name and address of your 
   store, the Owner part is about you and the Login Information will allow you 
   to access the admin Panel of the your store in the marketplace. If need be, 
   you can update those informations later in the Vendor `Settings`_

3. Click Register. 

Notifications 
*************

After the registration, you will receive an email notification confirming that 
your registration is complete.

.. note:: You will not be able to log into your account on the marketplace 
    until a marketplace staff member approves your registration.

You will get another email notification when your registration is approved.

Admin Panel
^^^^^^^^^^^

From the marketplace home page, navigate to `/admin`, type in your username 
and password and click the Login button to access the admin panel. You will 
be shown your dashboard with a summary of your sales.

Settings
^^^^^^^^

Navigate to the `Vendor Settings` page by clicking `Vendor Settings` 
under the `Settings` category from the Shuup Admin menu.

You can update the name, description and logo of the Vendor and use the tabs 
on the left-hand side to update the contact address and the opening periods.

Click on the `Go to vendor page` button to be taken to your vendor page on the 
store front.

Product Management
^^^^^^^^^^^^^^^^^^

Navigate to the `Vendor Products` page by clicking `Products` under the 
`Products` category from the Shuup Admin menu.

On this page, you will find all the products available to the marketplace. To 
find a product more easily, you can filter them by name. You can manage your 
stocks, start and stop selling products and set the price. If no price is set, 
the default price will be used.

Orders
^^^^^^^

Navigate to the `Vendor Orders` page by clicking `Vendor Orders` under the 
`Orders` category from the Shuup Admin menu.

On this page, you will find all the orders that have been made for the vendor. 
There are multiple filters available to single orders out. 

Click on an order to see the order information like the order number and 
reference, the customer name, email, billing and shipping address as well as 
the product name, quantity and price.

Depending on your marketplace configuration, it might also be possible to 
create a shipment, set the tracking code or the order status.

As a Marketplace Staff Member
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Create a new Vendor
^^^^^^^^^^^^^^^^^^^

1. Navigate to the Vendors Management page by clicking `Vendor Management` 
   under the `Settings` category from the Shuup Admin menu.

2. Click on the `+ Create new` button.

3. Fill out the Vendor's name. You can also add a description, a logo and 
   management users. Make sure the `Enabled` and `Approved` checkboxes are 
   selected.

4. Click on the  `Contact Address` tab on the left-hand side to fill out the 
   contact name and address.

5. You can set up opening periods in the `Opening periods` tab on the left-hand 
   side.

6. Click on the `Save` button.

The Vendor will receive an email notification for the registration and another 
one for the approval if the `Approved` checkbox was selected during the 
creation process. Vendors can log in their admin panel as soon as they are 
approved.

Se :ref:`Notifications` to set up customized Notifications

Approving a Vendor
^^^^^^^^^^^^^^^^^^

1. Navigate to the Vendors Management page by clicking `Vendor Management` 
   under the `Settings` category from the Shuup Admin menu.

2. Select the Vendor you want to approve.

3. You can edit the Vendor's informations such as their name, description 
   logo, contact address and opening periods.

4. Select the `Approved` checkbox.

5. Click `Save`.

The Vendor will receive an email notification once their registration is 
approved. Vendors can log in their admin panel as soon as they are 
approved.

Se :ref:`Notifications` to set up customized Notifications

Orders from all Vendors
^^^^^^^^^^^^^^^^^^^^^^^

Navigate to the `Vendor Orders` page by clicking `Vendor Orders` under the 
`Orders` category from the Shuup Admin menu.

On this page, you will find all the orders that have been made for  all the 
vendors in the marketplace. There are multiple filters available to single 
orders out. 

Click on an order to see the order information like the order details, the 
customer name, email, billing and shipping address as well as the product name, 
quantity and price.

Depending on your marketplace configuration, it might also be possible to 
create a shipment, set the tracking code or the order status.

See :ref:`Orders` for more information.

