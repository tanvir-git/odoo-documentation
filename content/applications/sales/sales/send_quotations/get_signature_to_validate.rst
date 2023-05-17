=========================================
Online signatures for order confirmations
=========================================

The Odoo *Sales* application provides customers with the opportunity to confirm orders via an
online signature directly on the sales order. Once electronically signed by the customer, the
salesperson attached to the sales order is automatically notified that the order is confirmed.

Activate online signatures
==========================

To activate the *Online Signature* feature, go to :menuselection:`Sales app --> Configuration -->
Settings`, scroll to the :guilabel:`Quotations & Orders` heading, and activate the
:guilabel:`Online Signature` feature by checking the box beside it, and clicking the
:guilabel:`Save` button in the top-left corner.

.. image:: get_signature_to_validate/signature-setting.png
   :align: center
   :alt: How to enable online signature on Odoo Sales.

.. note::
   If you are familiar with the documentation explaining :doc:`quote_template`, the
   :guilabel:`Online Signature` feature for each quotation template is found under the
   :guilabel:`Confirmation` tab.

   .. image:: get_signature_to_validate/signature-confirmation-tab.png
      :align: center
      :alt: How to enable online signature on Odoo Sales.

   On standard quotations, the :guilabel:`Online Signature` feature is located under the
   :guilabel:`Other Info` tab.

   .. image:: get_signature_to_validate/signature-other-info-tab.png
      :align: center
      :alt: How to enable online signature on Odoo Sales.

Order confirmations with online signatures
==========================================

When quotations are sent to clients, there's an option for them to :guilabel:`Sign & Pay` directly
on the quotation. When clicked, clients have the option to draw a signature, automatically fill in
the field with an automated signature, or load a file from their computer.

.. image:: get_signature_to_validate/signature-validate-order.png
   :align: center
   :alt: How to confirm an order with a signature on Odoo Sales.

Once signed, the various payment method options become available. Then, when the quotation is paid
and confirmed, a delivery order is automatically created.

.. seealso::
   :doc:`/applications/sales/sales/send_quotations/quote_template`
