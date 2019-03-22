Payment and Shipping
====================

In Shuup, payment and shippings choices are associated with particular
service providers. These may be provided by Shuup's build-in carriers
or payment process, or may be provided by payment or shipping-related
addons.

Service Providers
~~~~~~~~~~~~~~~~~

Creating a Payment/Service Provider
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Navigate to the Service Providers admin page by clicking `Service
   Providers` under the `Shops` category from the Shuup Admin menu.

..   .. image:: payment-and-shipping/service-providers-menu.png

2. Click the `New service provider` button in the Service Providers
   admin toolbar.

   .. image:: payment-and-shipping/new-service-provider-button.png

3. Select the provider *type* from the dropdown.

   .. image:: payment-and-shipping/new-service-provider.png

   .. note::
      Some classes of providers may require extra fields. If so, these
      should appear when you select the provider from the dropdown.

4. Enter the name, logo, enabled status, and any additional fields.

   .. image:: payment-and-shipping/new-carrier.png

5. Click `Save` to create the service provider.


6. Once saved, click `Create payment method` or `Create shipping method`
   to create a payment or shipping method associated with this payment
   provider.

   See `Creating a Payment Method`_ and `Creating a Shipping Method`_.

   .. image:: payment-and-shipping/create-payment-method.png

Payment Methods
~~~~~~~~~~~~~~~

Creating a Payment Method
^^^^^^^^^^^^^^^^^^^^^^^^^

1. Navigate to the Payment Method admin by clicking `Payment Methods`
   under the `Shops` category from the Shuup Admin menu.

..   .. image:: payment-and-shipping/payment-methods-menu.png

2. Click the `New payment method` button in the Payment Methods admin
   toolbar.

   .. image:: payment-and-shipping/new-payment-method-button.png

3. Select a payment provider from the `payment processor` dropdown as
   well as a payment service from the `service` dropdown.

   .. image:: payment-and-shipping/select-payment-method-provider.png

4. Enter the remaining information for the method.

..   .. image:: payment-and-shipping/new-payment-method.png

5. Click `Save` to create the payment method.

Shipping Methods
~~~~~~~~~~~~~~~~

Creating a Shipping Method
^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Navigate to the Shipping Method admin by clicking `Shipping Methods`
   under the `Shops` category from the Shuup Admin menu.

..   .. image:: payment-and-shipping/shipping-methods-menu.png

2. Click the `New shipping method` button in the Shipping Methods admin
   toolbar.

   .. image:: payment-and-shipping/new-shipping-method-button.png

3. Select a shipping provider from the `carrier` dropdown as well as a
   shipping service from the `service` dropdown

   .. image:: payment-and-shipping/select-shipping-method-provider.png

4. Enter the remaining information for the method.

   .. image:: payment-and-shipping/new-shipping-method.png

5. Click `Save` to create the shipping method.

Behavior Components
~~~~~~~~~~~~~~~~~~~

When a customer checks out, they are presented the choice of any
available payment methods for their order.

Whether a particular payment method is applicable to an order depends
on its behavior, which is comprised of any number of `behavior
components`.

`Behavior components` are essentially just individual components that,
when taken together, define.

1. Whether a payment method is available for an order
2. The amount to charge for that payment method, if available

Shuup also ships with the following basic components (although
behavior components can also be added by `Addons`):

Fixed cost
  Add a fixed cost.
Waiving cost
  Add a cost that is only applied up to a price limit.
Weight limits
  Limit availability of the service based on total weight of products.
Weight-based pricing range
  Add a cost to the order if it is within a specific weight range.

.. note::
   If there are multiple valid weight-based pricing ranges for an
   order, the cheapest-option will be selected.

Adding a Behavior Component to a Method
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Navigate to the Shipping or Payment Methods admin by clicking
   `Shipping Methods` or `Payment Methods` under the `Shops`
   category from the Shuup Admin menu.

..   .. image:: payment-and-shipping/payment-methods-menu.png

2. Select the shipping or payment method to which you want to add
   behavior components.

   .. image:: payment-and-shipping/select-payment-method.png

3. Click the `Behavior` tab on the left-hand side of the screen.

   .. image:: payment-and-shipping/behavior-tab.png

4. Select behavior component type from the `Behavior component type`
   dropdown and press the `Add component` button to add a blank form for
   the selected behavior component.

   .. image:: payment-and-shipping/add-component.png

5. Enter the behavior component settings, repeat as necessary to add
   more behavior components.

6. Click `Save` to save the behavior components for the selected method.
