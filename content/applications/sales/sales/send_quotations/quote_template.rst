===================
Quotation templates
===================

Creating custom quotation templates saves a lot of time. By using preconfigured quotation
templates, completed quotations are able to be sent at a much faster pace.

Configuration
=============

In order to create custom quotations, the *Quotation Template* feature must be enabled. To do that,
navigate to :menuselection:`Sales app --> Configuration --> Settings`, and scroll to the
:guilabel:`Quotations & Orders` heading.

In that section, check the box beside the :guilabel:`Quotation Templates` feature. Doing so reveals
a new :guilabel:`Default Template` field, in which a quotation template can be chosen from a
drop-down menu, and Odoo uses that template as its default quotation template.

.. image:: quote_template/quotations-templates-setting.png
   :align: center
   :alt: How to enable quotation templates on Odoo Sales.

Also, upon activating the :guilabel:`Quotation Template` feature, a direct link to
:guilabel:`Quotation Templates` appears beneath the :guilabel:`Default Template` field o the
settings page. clicking the :guilabel:`Quotation Templates` link reveals a separate
:guilabel:`Quotation Templates` page, where all the templates can be found, examined, and edited.
New quotation templates can also be created on the :guilabel:`Quotation Templates` page, as well.

.. note::
   Upon activating the :guilabel:`Quotation Templates` feature, it is recommended to also activate
   the *Quotation Builder* feature, located in the right column, beside the
   :guilabel:`Quotation Templates` feature. This feature aides in the design and cusotmization of
   quotation templates. It is also automatically install the Odoo *Website* application, as well.

.. image:: quote_template/quotations-builder-setting.png
   :align: center
   :alt: How to enable quotation builder on Odoo Sales.

Before leaving the settings page, don't forget to click the :guilabel:`Save` button to activate the
feature(s), and save all changes.

Create quotation templates
==========================

To view all quotation templates, click the :guilabel:`Quotation Templates` link on the settings
page, or navigate to :menuselection:`Sales app --> Configuration --> Quotation Templates`. Both
options reveal the :guilabel:`Quotation Templates` page, where all the quotation templates can be
found, edited, and/or created.

To create a new quotation template, click the :guilabel:`Create` button, located in the upper-left
corner. Doing so reveals a blank quotation template form that can be customized in a number of
ways.

.. image:: quote_template/blank-quotation-template.png
   :align: center
   :alt: Create a new quotation template on Odoo Sales

Start by entering a name for the template in the :guilabel:`Quotation Template` field. Then, in the
:guilabel:`Quotation expires after` field, designate how many days the quotation template will
remain valid for, or leave the field on the default `0` to keep the template valid indefinitely.

In the :guilabel:`Company` field, designate to which company this quotation template applies, if
working in a multi-company enviornment.

Beneath those fields are three tabs: :guilabel:`Lines`, :guilabel:`Optional Products`,
:guilabel:`Confirmation`.

In the :guilabel:`Lines` tab, products can be added to the quotation template.

In the :guilabel:`Optional Products` tab, optional products can be added to the quotation template.

And, in the :guilabel:`Confirmation` tab, the options to require an :guilabel:`Online Signature`
and/or :guilabel:`Online Payment` are available. There's also an option to add a
:guilabel:`Confirmation Mail` to the quotation template, as well.

.. image:: quote_template/quotations-templates-confirmation-tab.png
   :align: center
   :alt: Allow your customers to sign electronically or to pay online on Odoo Sales

Design quotation templates
==========================

In the upper-left corner of the quotation template form, there's a :guilabel:`Design Template`
button. When clicked, Odoo reveals a preview of the quotation template on the front-end of the
website, with a *Template Header* informing that this content will appear on all quotations using
this specific template.

To edit the content, look, and overall design of the quotation template, click the :guilabel:`Edit`
button in the upper-right corner. Doing so reveals a variety of design elements and feature-filled
building blocks.

.. image:: quote_template/design-quotation-edit.png
   :align: center
   :alt: Design your quotation template on Odoo Sales

Drag and drop any desired building blocks onto the blank quotation template, and proceed to further
customize the content to fit any business need. When all blocks and customizations are complete,
click the :guilabel:`Save` button to put those configurations into place.

.. image:: quote_template/quotations-building-blocks.png
   :align: center
   :alt: Drag and drop building blocks to create your quotation template on Odoo Sales

Use quotation templates
=======================

When creating a quotation (:menuselection:`Sales app --> Create`), choose a preconfigured template
in the :guilabel:`Quotation Template` field drop-down menu.

.. image:: quote_template/quotations-templates-field.png
   :align: center
   :alt: Select a specific template on Odoo Sales

To view what the customer will see, click the :guilabel:`Customer Preview` smart button to see how
the quotation template will look on the front-end of the website.

.. seealso::
   - :doc:`/applications/sales/sales/send_quotations/get_signature_to_validate`
   - :doc:`/applications/sales/sales/send_quotations/get_paid_to_validate`
