=========
Templates
=========

Whenever creating a new spreadsheet, select one of the existing templates to speed up the creation
process.

Default reports
===============

Several report templates are available by default.

Accounting: budget reports
--------------------------

Budget reports compare a company's actual spending with its budget over a defined period. Two
templates are available, one uses quarterly intervals (:guilabel:`Budget Report (Quarterly)`), while
the other uses monthly intervals (:guilabel:`Budget Report (Monthly)`).

The cells under the :guilabel:`Actuals` column are automatically filled in with the amount of money
actually made and spent over the related period (month or quarter). The data is taken from posted
journal entries on every :ref:`income and expense account <chart-of-account/type>`.

To view your budget's performance, fill the cells under the :guilabel:`Budget` column with how much
money you expect to make (:guilabel:`Income` rows) and spend (:guilabel:`Expenses` rows) monthly per
account.

The performance (:guilabel:`Perf.`) column then compares actuals to its related budget, expressed as
a percentage.

Lastly, the :guilabel:`Net Profit` row represents the total :guilabel:`Income` minus the total
:guilabel:`Expenses` for the actuals and budget columns.

CRM: pipeline revenue reports
-----------------------------

Two pipeline revenue reports are available. The :guilabel:`Pipeline Revenue Report (Monthly)` is
dedicated to one-time revenue (:abbr:`NRR (non-recurring revenue)`), while the :guilabel:`MRR/NRR
Pipeline Revenue Report (Monthly)` also covers recurring revenue (:abbr:`MRR (monthly recurring
revenue)`).

.. tip::
   Enable :guilabel:`Recurring Revenues` by going to :menuselection:`CRM --> Configuration -->
   Settings`.

The cells under the :guilabel:`Actuals` column are automatically filled in with the amount of
monthly revenue from **won** opportunities.

To compute the revenue performance, fill in the monthly revenue targets.

- On the :guilabel:`Revenue by Team` sheet, fill in the cells under the :guilabel:`Target` columns
  for each sales team.
- On the :guilabel:`Revenue by Salesperson` sheet, open the :guilabel:`Targets` sheet and fill in
  the cells next to each salesperson. Use the :guilabel:`Monthly Factor` table below to adapt the
  main targets depending on the month of the year.

The :guilabel:`Performance` column then compares actuals to its related target, expressed as a
percentage.

Lastly, the :guilabel:`Forecasted` column gathers the monthly revenue of leads multiplied by their
:guilabel:`Probability` percentage.

.. note::
   For actuals and forecasts:

   - The :guilabel:`Expected Closing` date found on leads is used to assign them to a month.
   - The recurring monthly revenur is used even if the recurring plan's number of months is set to
     a different value than 1 month. For example, a yearly plan's revenue is divided by 12 months.

Save a spreadsheet as a template
================================

Any spreadsheet can be saved as a template. From the menu bar, click :menuselection:`File --> Save
as template`. Modify the :guilabel:`Template Name` given by default if necessary and click
:guilabel:`Confirm`.

.. note::
   Templates are available to all users on the database.

Manage and edit templates
=========================

Manage templates by going to :menuselection:`Documents --> Configuration --> Settings`. Remove the
:guilabel:`My Templates` :ref:`filter <search/preconfigured-filters>` to view all templates in the
database.

To edit an existing template, click `Edit`. Modifications are automatically saved.

.. tip::
   Use the download button (:guilabel:`⭳`) under the :guilabel:`Data` column to export a template
   in JSON format. The file can be imported into another database.
