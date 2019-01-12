=============================
Completely reset the database
=============================

.. NOTE::

    Work in progress: This page is not finished yet...

Back to factory settings
========================

It happens especially in the beginning, when you are trying things and learning a lot, that you want to begin at the very start again, to configure OpenPetra the way you want it.

To achieve this, you first need to download the clean database: Go to the URL https://github.com/openpetra/demo-databases/blob/master/clean.yml.gz and click the "Download" Button in order to save the file locally.

The you sign in with your ``SYSADMIN`` user, and in the sidebar menu you go to *System Management*, and select *Database*.

Then you click the red button with the label *Restore all data from backup*.

A dialog will open. Here you select the file, that you just have downloaded.

Then you logout, and then sign in again, with the user ``SYSADMIN`` and the password ``CHANGEME``.

You should immediately change the password: In the menu in the top bar, select *Settings* / *Change Password*.

Now you again follow the instructions at :ref:`specify_your_email_address` ...
