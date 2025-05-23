==============================
Stock Barcodes Automatic Entry
==============================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:adaecd83a7050b30a46869506bd2d6963ad21d03d54de6a32d5899f26f981139
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fstock--logistics--barcode-lightgray.png?logo=github
    :target: https://github.com/OCA/stock-logistics-barcode/tree/13.0/stock_barcodes_automatic_entry
    :alt: OCA/stock-logistics-barcode
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/stock-logistics-barcode-13-0/stock-logistics-barcode-13-0-stock_barcodes_automatic_entry
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/stock-logistics-barcode&target_branch=13.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module will automatically trigger the click event on a button with the class
'barcode-automatic-entry' after a barcode scanned has been processed.

**Table of contents**

.. contents::
   :local:

Usage
=====

To use this module, you need to:

* Define, in the view, the button that will be clicked automatically as the example below:

.. code-block:: xml

    <button name="action_automatic_entry" type="object" string="Automatic entry" icon="fa-plus"
            class="btn-primary barcode-automatic-entry" invisible="1"
    />

* Define the logic to be executed upon button clicking

.. code-block:: python

    def action_automatic_entry(self):
        # Execute specific logic
        return

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/stock-logistics-barcode/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/stock-logistics-barcode/issues/new?body=module:%20stock_barcodes_automatic_entry%0Aversion:%2013.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* ForgeFlow S.L.

Contributors
~~~~~~~~~~~~

* Adrià Gil Sorribes <adria.gil@forgeflow.com>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-AdriaGForgeFlow| image:: https://github.com/AdriaGForgeFlow.png?size=40px
    :target: https://github.com/AdriaGForgeFlow
    :alt: AdriaGForgeFlow

Current `maintainer <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-AdriaGForgeFlow| 

This module is part of the `OCA/stock-logistics-barcode <https://github.com/OCA/stock-logistics-barcode/tree/13.0/stock_barcodes_automatic_entry>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
