==========================================
Quotation deadlines to stimulate customers
==========================================

When sending quotations, it's important to set a deadline to encourage customers to act and confirm
orders in a timely manner.

Setting deadlines on quotations entices customers to finalize the process because they might fear
that they'll miss out on a good deal. Quotation deadlines are also useful because they can be used
as protection for a company, in case an order has to be fulfilled at a price that is no longer
profitable for the business.

Expiration date deadlines
=========================

With Odoo *Sales*, it's possible to instantly add an expiration date in the :guilabel:`Expiration`
field of a quotation or sales order.

.. image:: deadline/quotation-deadlines-expiration-field.png
   :align: center
   :alt: How to configure deadlines on Odoo Sales.

Deadlines in quotation templates
================================

The Odoo *Sales* application also makes it possible to add a deadline to every quotation template,
as well. Whenever a specific quotation template is used in a quote, its associated deadline is
automatically applied.

To add a deadline to a quotation template, navigate to :menuselection:`Sales app --> Configuration
--> Quotation Templates`, and either select the desired quotation template to which a deadline
should be added, or click :guilabel:`Create` to build a new quotation template from scratch.

On the quotation template detail page, click the :guilabel:`Edit` button to edit the quotation.

Then, add a specific number of days to the :guilabel:`Quotation expires after` field, located
beneath the quotation template name. The number of days represents how long the quotation will be
valid for, before it expires. When done, click :guilabel:`Save`.

Check out the documentation on :doc:`/applications/sales/sales/send_quotations/quote_template` to
learn more.

.. image:: deadline/quotation-deadlines-expires-after.png
   :align: center
   :alt: How to use deadline in a quotation template on Odoo Sales.

.. tip::
   By clicking the :guilabel:`Customer Preview` button on a quotation, Odoo clearly displays when
   that specific offer expires. As a reminder, the number of days is the same as those mentioned in
   the quotation template (if a quotation template was used for the initial quotation).

   .. image:: deadline/quotation-deadlines-preview.png
      :align: center
      :alt: How customers will see deadlines on Odoo Sales.

.. seealso::
   :doc:`/applications/sales/sales/send_quotations/quote_template`
