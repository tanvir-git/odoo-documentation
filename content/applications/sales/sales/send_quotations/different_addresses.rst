==============================================
Deliveries and invoices to different addresses
==============================================

People and businesses often use separate addresses for billing (invoicing) and shipping (delivery)
purposes. With the Odoo *Sales* app, contacts can have different specified addresses for delivery
and invoicing.

Settings
========

To properly utilize multiple addresses in Odoo, go to :menuselection:`Sales app --> Configuration
--> Settings` and scroll down to the :guilabel:`Quotations & Orders` heading. Then, check the box
next to :guilabel:`Customer Addresses`, and click :guilabel:`Save`.

.. image:: different_addresses/customer-addresses-setting.png
   :align: center
   :alt: Activate the Customer Addresses setting.

Configure the contact form
==========================

To add multiple addresses to a contact, navigate to the :menuselection:`Contacts` app (or to
:menuselection:`Sales --> Orders --> Customers`, and clear any default filters from the search
bar), then click on the desired customer to open their contact form.

From the contact form, click :guilabel:`Edit` and, under the :guilabel:`Contacts & Addresses` tab,
click :guilabel:`Add`. Doing so reveals a :guilabel:`Create Contact` pop-up window, in which
additional addresses can be configured.

.. image:: different_addresses/contact-form-add-address.png
   :align: center
   :alt: Add a contact/address to the contact form

On the :guilabel:`Create Contact` pop-up form, start by clicking the default :guilabel:`Other
Address` field to reveal a drop-down menu of address-related options.

Select any of the following options:

- :guilabel:`Contact`
- :guilabel:`Invoice Address`
- :guilabel:`Delivery Address`
- :guilabel:`Other Address`
- :guilabel:`Private Address`

Once an option is selected, proceed to enter the corresponding contact information that should be
used for that specified address type.

.. image:: different_addresses/create-contact-window.png
   :align: center
   :alt: Create a new contact/address on a contact form.

Then, click :guilabel:`Save & Close` to save the address and close the :guilabel:`Create Contact`
window. Or, click :guilabel:`Save & New` to save this address and immediately input another one.

Address added to quotations
===========================

When a customer is added to a quotation, the :guilabel:`Invoice Address` and :guilabel:`Delivery
Address` fields autopopulate with the corresponding addresses specified on the customer's contact
form.

.. image:: different_addresses/quotation-address-autopopulate.png
   :align: center
   :alt: Invoice and Delivery Addresses autopopulate on a quotation.

The :guilabel:`Invoice Address` and :guilabel:`Delivery Address` can also be edited directly from
the quotation by clicking the :guilabel:`Edit` button, and then clicking the :guilabel:`External
link` buttons next to each address line (represented by an arrow in a square).

These addresses can be updated at any time to ensure accurate invoicing and delivery.

When (and if) any changes are made, remember to click :guilabel:`Save` to save the changes.
