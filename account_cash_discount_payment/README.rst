.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :alt: License: AGPL-3

=============================
Account Cash Discount Payment
=============================

Extends Account Cash Discount Base and Payment Order modules to let you
add invoices on payment order considering the cash discount on it.
When an invoice with cash discount is added to a payment order,
the amount proposed on payment line will be the residual amount discount deducted,
provided that the due date has not expired.

This module also offers to search by discount due date to add invoices on
payment order and add discount amount on payment line.

Usage
=====

To use this module you can use payment order

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/96/10.0

For further information, please visit:

 * https://www.odoo.com/forum/help-1

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/account-payment/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed feedback
`here <https://github.com/OCA/account-payment/issues/new?body=module:%20account_cash_discount_payment%0Aversion:%208.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Credits
=======

Contributors:
-------------

* Christelle De Coninck (ACSONE) <christelle.deconinck@acsone.eu>
* Stéphane Bidoul (ACSONE) <stephane.bidoul@acsone.eu>
* Adrien Peiffer (ACSONE) <adrien.peiffer@acsone.eu>
* Benjamin Willig (ACSONE) <benjamin.willig@acsone.eu>

Maintainer:
-----------

.. image:: http://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: http://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose mission is to support the collaborative development of Odoo features and promote its widespread use.

To contribute to this module, please visit http://odoo-community.org.
