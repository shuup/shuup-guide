.. _xtheme:

******
Xtheme
******


Xtheme Content Summary
======================
    * :ref:`xtheme explain`
    * :ref:`xtheme tools`
        * :ref:`xtheme tools status`
        * :ref:`xtheme tools modes`
    * :ref:`xtheme edit`
        * :ref:`xtheme edit placeholder`

.. _xtheme explain:


Xtheme explanation
===================

What is the xtheme
------------------

The xtheme allows the site admin and staff to make both
small and large changes to the look of there site.


Requirements
------------

To be able to make modifications to the theme you will
need to be logged in with a admin or staff account.


.. _xtheme tools:

Available tools
===============

When accessing any front pages and while logged in with admin or staff account.
You will see a bar on top of the site and all it's functionality we will cover here.

.. figure:: front/xtheme/toolbar.png
    :width: 80%
    :align: center
    :alt: orders-location-in-menu
    :figclass: align-center

    The red number corresponds to the closest red box,
    and also to the number in list below.

1. **Site status**

    This will tell you as a site owner if the site is live or under maintenance.


2. **Viewing mode**

    These two icons tells you what content you are viewing right now.
    This is important to keep track of due to that the content so on the site may vary.


3. **Edit page**

    By clicking this button you will be able to access and edit the placeholders that are available on the current page.


4. **Theme custom CSS/JS**

    Links to the snippets in the admin panel. Here you will be able to make site wide javascripts, css and html content.
    This snippets have one limitation and that is they will not be renderd in when a user is in the admin panel.


5. **Shop admin**

    Opens up the admin panel in a new tab.


6. **Tools**

    When clicking on "tools" there will be a drop down where you can changes what viewing mode you are in. 
    Based on what viewing mode you are in the icons will change, please refer to point 2 in this list.


.. _xtheme tools status:

Site status
-----------

There are two statuses the site can be in:

1. **Live**
    .. figure:: front/xtheme/live_icon.png
        :width: 10%
        :alt: person contact icon
    
    This means that the site is live and anyone can come and view it.
    This is the status that should be shown as much as possible.

2. **Maintenance**
    .. figure:: front/xtheme/maintenance_icon.png
        :width: 20%
        :alt: person contact icon

    Maintenance mode can be enabled in the admin plane by the site admin.
    When the site is in maintenance mode the users will not be able to view the site.
    The admin panel is still available for vendors, staff and the admin.
    The front pages will also be available for both admin and staff.

    .. note::
        The maintenance is recommended to use if there will be a large  change made to the front using placeholder.


.. _xtheme tools modes:

Viewing modes
-------------

1. **Person contact mode**
    .. figure:: front/xtheme/person_contact.png
        :width: 10%
        :alt: person contact icon

    In this mode you will also be able to change if all products and categories are shown,
    or if only products and categories that are visible should be shown.

2. **Guest mode**
    .. figure:: front/xtheme/guest_user.png
        :width: 10%
        :alt: guest user icon

    In this mode you will only be able to se placeholder that are shown to anonymous users.
    A anonymous users is a user who as not logged in.
    In this mode you will only be able to se placeholders that are visible to anonymous users.

3. **Company contact mode**
    .. figure:: front/xtheme/company_user.png
        :width: 10%
        :alt: company contact icon

    In this mode you will be able to se all placeholders,
    but you will not be able to change if all products and categories are shown or only visible once.

4. **Products and categories shown**

    .. figure:: front/xtheme/view_all_products.png
        :width: 10%
        :alt: green eye icon

    .. figure:: front/xtheme/view_limeted_products.png
        :width: 10%
        :alt: red eye icon

    When the icon is red you will on see visible products and categories,
    the in when it's green you will see all products


.. _xtheme edit:

Edit page
=========

When clicking the edit button the page will change a bit and you will see all available placeholders in the mode you are in.

All of the blue dashed line surrounds one placeholder.
To edit a place holder simply hover over the placeholder you want to edit,
when doing this the background will change to have a shade of blue over it and the dashed lines will become solid.

.. note:
    * Available placeholders changes depending on your mode.
    * The text in the upper right corner explains to which users the content will be shown.


.. figure:: front/xtheme/edit_page.png
    :width: 90%
    :align: center
    :alt: orders-location-in-menu
    :figclass: align-center


.. _xtheme edit placeholder:

Edit placeholder
----------------

When click on empty placeholders there will not be any rows shown.
But if you are editing a placeholder where there is content there will be rows that show up here.

    .. figure:: front/xtheme/edit_plugin.png
        :width: 90%
        :align: center
        :alt: orders-location-in-menu
        :figclass: align-center


1. **Publish changes**

    When clicking this button all the change you have made to the placeholder will go live.
    Before clicking this all the change will just be viewable in it's placeholder editor.


2. **Plugin**

    This show the place that this plugin will be shown in.
    This means that you can have different plugins next to each other.


3. **Selected plugin**

    The plugin that has a blue background is the current selected plugin.
    This is important to check before doing change in point 9.


4. **Add plugin**

    Adds a plugin to the row. Remember that this will make the plugins that
    already are on the row smaller in there width.


5. **Delete row**

    Deletes the hole row. This action will not only delete the selected plugin but the hole row.


6. **Move row**

    Move the hole row up or down. You can click and hold down your left mouse button then drag the hole row to the desired place.


7. **Add new row**

    This adds a new row that spans the hole width of the place holder.


8. **Delete cell**

    Delete the currently selected plugin. The currently selected plugin can be
    determined by looking at which row has a different background. Please refer to point 3.


9. **Plugin select**

    Select the plugin you want to select for the current row.


10. **Save plugin**

    After making change to the plugin you
    must remember to save it before publishing, else your changes will be deleted.