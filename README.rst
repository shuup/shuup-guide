Shuup Guide
===========

This is a guide for merchants on how to use Shuup.

For more information about Shuup, see https://shuup.com/ and `Shuup
at GitHub <https://github.com/shuup/shuup>`_.

Set up
------

1. Install requirements by runing `pip install -r requirements.txt`

2. Run sphinx-reload . in the root of the project

    Then open up http://localhost:5500.

    All change made to the .rst files in the source
    folder will automatically reload the server.

Commiting
---------

When you have updated or created a new documentation page. Commit it and push normaly but make the PR **from your branch to dev-updates**.

Creating new pages
------------------

Create a new .rst file in the `source/` folder. Then add the name of the file to the `source/index.rst` file in the `toctree`.

Formatting
----------

Look how the source/order.rst is formatted to see how you should format the page you are working on.

Copyright
---------

Copyright (C) 2019 by Anders Innovations Inc, DBA Shuup. support@shuup.com

Shuup is International Registered Trademark & Property of Anders Innovations 
Inc, DBA Shuup, Business Address: 1500 West Georgia St Suite 1300, Vancouver, 
BC, V6G 2Z6.

License
-------

Shuup Guide is licensed under a Creative Commons Attribution-ShareAlike
4.0 International License.

You should have received a copy of the license along with this work.  If
not, see http://creativecommons.org/licenses/by-sa/4.0/.

CLA
---

Contributor License Agreement is required for any contribution to this
project.  Agreement is signed as a part of pull request process.  See
the CLA.rst file distributed with Shuup Guide.
