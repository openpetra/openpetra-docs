===================================
Configuration of the partner module
===================================

.. NOTE::

    Work in progress: This page is not finished yet...

Maintain Categories
===================

Categories are like special types that you can assign to your contacts and put them into groups.

For example you can have a category called SPONSOR, which you assign to all your partners that are sponsoring a child or project.

Or you have a category for BOARDMEMBER, or WORKER.

In the sidebar menu go to *Partner*, select *Setup*, and then select *Configuration of Categories*.

.. _figure-category_list:

.. figure:: images/category_list.png
   :scale: 50%

   Edit categories

You can delete a category, or add new categories.

The dialog looks like this:

.. _figure-category_edit:

.. figure:: images/category_edit.png
   :scale: 50%

   Edit category

Maintain Subscriptions
======================

You can specify, which recurring publications each of your contacts wants to receive.

You need to configure the type or name of such a publication.

It can be an annual report, or a recurring newsletter.

In the sidebar menu go to *Partner*, and select *Setup*, and then select *Configuration of Subscriptions*.

.. _figure-publication_list:

.. figure:: images/publication_list.png
   :scale: 50%

   Maintain Subscriptions

You can delete a subscription or add a new subscription.

The dialog looks like this:

.. _figure-publication_edit:

.. figure:: images/publication_edit.png
   :scale: 50%

   Edit subscription

Import your existing addresses
==============================

You already have a list of addresses that you would like to import?

In order for this to work, you must rearrange the addresses in Excel or LibreOffice Calc into a format as illustrated here:

::

  "Title";"FirstName";"FamilyName";"Street";"PostCode";"City";"Country";"Email";"Mobile";"Phone"
  Herr;Arthur;Müller;"Wiesenstr. 8";"12345";"München";"DE";"mueller@gibts.net";0151-0000000000;01234-123123
  Herr und Frau;"Hans-Walter und Martina";"Meier";"Bäckerweg 3";"98765";"Frankfurt am Main";"DE";"meier@gibtsauch.net";;;

The order of the columns can be random, but the caption of the column is important.

You have to save the file in the file format CSV. We currently only support the semicolon (;) as separator.

Now go in the side bar menu and click on *Partner*, then select *Partner*, and select *Import partners*.

Then click the button with the label *Import partners from CSV file*.

You will get a dialog where you have to select the file that you just saved.

After a successful import you can see the list of your partners at *Partner* / *Partner* / *Maintain Partners*.
