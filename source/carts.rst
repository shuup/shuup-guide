Carts
=====

When a customer adds a product to their cart, the system created a cart object 
which is visible from the admin menu by navigating to `Orders > Carts`.

There you can see a table rendering all the carts ever made by customers. It 
contains data like the date and time it was created and updated, whether or 
not it was abandoned, the shop and the product count.

The filter button on the top right corner allows you to filter out carts
according to each table column.

Update the Cart Inactivity Delay
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Although it is possible to filter out carts according to their creation or 
updated dates, you might want to make sure that carts that are still active 
are not rendered on the Carts table by default. It is possible to add a delay 
of inactivity before the cart is rendered in the Carts table.

1. Navigate to the `Shops` menu by clicking `Shops` in the `Shops` category.
2. Click on the shop for which you want to add a delay.
3. Click the `Cart Inactivity Delay` tab on the left-hand side of the screen.
4. Input the number of hours the cart has to be inactive for before being 
   added to the Carts table.
5. Click `Save`.