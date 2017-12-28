
Using Launchpad
===============

Create a Launchpad account
--------------------------

If you don't have a Launchpad account already, use the `registration page <https://login.launchpad.net/+login>`_ to create a new one.

Edit the languages for your account and add all the languages you are fluent in.


Join the translation team for your language
-------------------------------------------

To see all the languages and their current status, go to `Translation status by language <https://translations.launchpad.net/linuxmint/latest/>`_ and click on :guilabel:`View all languages`.

.. figure:: images/launchpad1.png
    :width: 500px
    :align: center

Click on your language:

.. figure:: images/launchpad2.png
    :width: 500px
    :align: center

Click on the name of the team which is responsible for translations in your language:

.. figure:: images/launchpad3.png
    :width: 500px
    :align: center

Click :guilabel:`Join the team`.


Translate using Launchpad
-------------------------

Once you've joined the translation team, you can start translating.

Click on your language, choose a project which has missing translations and click on the number of untranslated items.

.. figure:: images/launchpad4.png
    :width: 500px
    :align: center

At the top of the page, make sure to be in ``Reviewer mode`` (otherwise your translations won't be approved automatically and they will wait for somebody else to review them).

Using POEdit
============

If you want to translate faster, you can download the translations as a ``.po`` file, edit that file with a tool called ``poedit`` and upload the edited ``.po`` file back into ``Launchpad``.


.. _download-ref:

Download the translations
-------------------------

Choose a project and click :guilabel:`Download translation`:

.. figure:: images/launchpad5.png
    :width: 500px
    :align: center

Choose ``PO format`` as the file format and click :guilabel:`Request Download`.

Wait for Launchpad to send you an email (this can take a little while). In the email you will find a download link to either the ``.po`` file directly, or an compressed archive containing the ``.po`` file.

Use POEdit
----------

To install POEdit, open a terminal and type:

.. code-block:: console

    apt install poedit

Open the ``.po`` file you got from Launchapd with POEdit:

.. figure:: images/poedit.png
    :width: 500px
    :align: center

Browse the menus and familiarize yourself with the keyboard shortcuts. If you use these shortcuts and the built-in spell checker, you'll translate much faster with POEdit than with Launchpad.

When finished, click :guilabel:`Save`.

Upload the translations back into Launchpad
-------------------------------------------

In Launchpad, click :guilabel:`Upload translation`.

.. figure:: images/launchpad6.png
    :width: 500px
    :align: center

Select your ``.po`` file and click :guilabel:`Upload`.

Click ``Translation Import Queue`` to reach the `Translation import queue for latest <https://translations.launchpad.net/linuxmint/latest/+imports>`_. If your upload is marked as ``Needs Review``, click the ``Edit`` button (which is symbolized by a pen symbol), choose the right template (i.e. project), and click ``Approve``.
