Customers
=========

Users
~~~~~

Creating a User
^^^^^^^^^^^^^^^

1. Navigate to the Users admin page by clicking `Users` under the
   `Contacts` category from the Shoop Admin menu.

2. Enter a valid username and password for the user as well as any
   other user information, then click the `Save` button in the
   to create the user account.

.. note::
   A user won't automatically receive notice that an account has been
   created for them.

   It may be to do so by sending them a password-reset email and having
   them create a new password. See `Sending Password-Reset Emails`_.

Creating a User From a Saved Contact
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Navigate to the Contacts admin page by clicking `Contacts` under the
   `Contacts` category from the Shoop Admin menu.

2. Select the contact for which you want to creaet a user account.

3. Click the `New User` button on the Contact admin toolbar.

4. Enter the new user's username and password information and click
   save to create the user account, which will now be associated with
   the selected contact information.

   See `Creating a User` for more information.

Managing User Passwords
^^^^^^^^^^^^^^^^^^^^^^^

Changing User Passwords
***********************

1. Navigate to the Users admin page by clicking `Users` under the
   `Contacts` category from the Shoop Admin menu.

2. Select the user whose password you want to change.

3. Click the `Actions` button on the user admin toolbar, and select
   `Change Password` from the dropdown menu.

4. Enter the new password in the `Change User Password` form and
   click `Save` in the toolbar to save the new password.

5. The password for the user account will now be updated.

Sending Password-Reset Emails
*****************************

1. Navigate to the Users admin page by clicking `Users` under the
   `Contacts` category from the Shoop Admin menu.

2. Select the user whose password you want to change.

3. Click the `Actions` button on the user admin toolbar, and select
   `Send Password Reset Email` from the dropdown menu.

4. On the next screen, click `Send Reset Email` to send the user a
   password reset email.

Editing User Permissions
^^^^^^^^^^^^^^^^^^^^^^^^

.. warning::

   Use caution when granting users administrative permissions.

1. Navigate to the Users admin page by clicking `Users` under the
   `Contacts` category from the Shoop Admin menu.

2. Select the user whose permissions you want to edit.

3. Click the `Actions` button on the user admin toolbar, and select
   `Edit Permissions` from the dropdown menu.

4. Check the permission levels that want to grant the user and click
   the `Save` button to save the user's permissions.

Deactivating a User
^^^^^^^^^^^^^^^^^^^

When users are deactivated, they remain in your system however they
will no longer be able to log in to their account.

To deactivate a user:

1. Navigate to the Users admin page by clicking `Users` under the
   `Contacts` category from the Shoop Admin menu.

2. Select the user you want to deactivate.

3. Click the `Deactivate User` button on the user admin toolbar.

4. The user will now be deactivated, and the `Deactivate User` button
   will be replaced with an `Activate User` button.

.. note:: The same steps can be followed to activate a deactivated user.

Contacts
~~~~~~~~

Shoop contacts store contact information such as address data, email, or
phone numbers, and a contact may or may not be associated with a
user account.

Creating a Contact
^^^^^^^^^^^^^^^^^^

1. Navigate to the Contacts admin page by clicking `Contacts` under the
   `Contacts` category from the Shoop Admin menu.

2. Click the `New contact` button on the Contacts admin toolbar.

3. Enter all basic details for the contact, including any required field

   If adding a contact of type *Person*, the `Name` field is required
   but unused. Instead, you will want to enter a temporary value into
   the `name` field and (optionally) provide the contact's first name
   last name.

   If adding a contact of type *Company*, the `Name` field is required
   and will be used as the company name. In this case, the first and
   last names will not be used.

4. Click the `Addresses` tabs on the left-hand side of the screen to
   enter billing and shipping addresss information for the contact.

5. Click the `Save` button to create the contact.

Creating a Contact From a User Account
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Navigate to the Users admin page by clicking `Users` under the
   `Contacts` category from the Shoop Admin menu.

2. Select the user whose permissions you want to edit.

3. Click the `Actions` button on the user admin toolbar, and select
   `Create Contact` from the dropdown menu.

4. Fill in the user's contact information, including any required
   fields, then save to create a saved contact for the user.

   See `Creating a Contact`_ for more information.

5. The contact will now be created and you will be taken to the new
   contact's admin page.

   Click the user's username to go back to the user's admin page.

Contact Groups
~~~~~~~~~~~~~~

In Shoop, contacts can be placed into different contact groups. These
groups can then be targetted for campaigns, discount pricing, or custom
behaviors.

.. Add information about default groups

Creating a Contact Group
^^^^^^^^^^^^^^^^^^^^^^^^

1. Navigate to the Contact Groups admin page by clicking `Contact
   Groups` under the `Contacts` category from the Shoop Admin menu.

2. Click the `Create new` button in the Contact Groups toolbar.

3. Select a name and price-display mode for your contact group.

4. Click the `Save` button to save your contact group

   Once the contact group has been saved, two new tabs will be
   automatically added to the group's admin page--a `Members` tab
   and one or more `Sales Range` tabs.

Editing Group Membership
^^^^^^^^^^^^^^^^^^^^^^^^

1. Navigate to the Contact Groups admin page by clicking `Contact
   Groups` under the `Contacts` category from the Shoop Admin menu.

2. Select the contact group whose membership you want to edit.

3. Click the `Members` tab on the left-hand side of the screen.

4. All contact group members will be listed.

To add a remove a contact from the group:

Adding a Contact
****************

To add a contact to a group:

1. If there are no blank contact rows, click the `Add more` button to
   add a blank contact row.

2. Click the `Select` button on a blank contact to launch the Contact
   selector popup. Select the contact you want to add.

3. Repeat as necessary to add more contacts.

4. Click `Save` to save the contact group.

Removing a Contact
******************

To remove a contact from a group:

1. Click the `Remove` checkbox next to any contacts you want to remove
   from the group.

2. Click `Save` to save the contact group membership.

Creating a Sales Range
^^^^^^^^^^^^^^^^^^^^^^

1. Navigate to the Contact Groups admin page by clicking `Contact
   Groups` under the `Contacts` category from the Shoop Admin menu.

2. Select the contact group to which you want to add a sales range.

3. Click the `(Shop Name) - Sales Ranges` tab on the left-hand side of
   the screen, where `(Shop Name)` is the name of the shop to associate
   with the sales range.

4. Enter a minimum and maximum value for the group's sales range.

   .. note::

      Leave the maximum value blank to set no maximum for the group.

      Set the minimum value to 0 to set no minimum for the group.

5. Click `Save` to save the contact group sales range. Contact group
   membership will automatically update based on customers' sales
   totals.


.. tip::
   Try creating a contact group for customers within a sales range
   value and target them for special discounts and promotions.
