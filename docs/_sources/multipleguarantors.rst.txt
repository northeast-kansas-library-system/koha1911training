.. .. [TODO] multiple guarantors

Add multiple guarantors to a patron
===================================

.. Open Otto Frosty
.. create Lisa Frosty BC FROST7744 as a child
.. Show how the "Add guarantor" button fails
.. Create Lisa anyway
.. Add Otto and Patricia as multipleguarantors

To add multiple guarantors to an account:
-----------------------------------------

1. Search for an existing child patron that already has a guarantor

  .. image:: /images/multipleguarantors.0010.png

2. Click on "Edit"

  .. image:: /images/multipleguarantors.0020.png

3. In the guarantors section, click on "Search to add"

  .. image:: /images/multipleguarantors.0030.png

4. Search for the name of the patron in the search box
  (note that the patron category must be chosen and that "Adult" is the default)

  (this is a work-around to a bug that allows children to be the guarantors for other children - it is even possible because of this bug for a patron to be their own guarantor)

  .. image:: /images/multipleguarantors.0040.png

5. When you find the patron you wish to be the guarantor, click on "Select"

  .. image:: /images/multipleguarantors.0050.png

6. You will now see two guarantors for this Patron

  .. image:: /images/multipleguarantors.0060.png

7. Click on "Save"

  .. image:: /images/multipleguarantors.0070.png

8. On the patron's "Details" tab, you will now see two multipleguarantors

  .. image:: /images/multipleguarantors.0080.png

9. All fees for this patron will count towards the $10.00 fee limit for *all* guarantors for this patron

  .. image:: /images/multipleguarantors.0091.png

|

  .. image:: /images/multipleguarantors.0092.png

10. If you select "Yes" for "Show checkouts to guarantors" all guarantors for this patron will see this patron's current check-outs in the OPAC

  .. image:: /images/multipleguarantors.0100.png

11. If you select "Yes" for "Show fines to guarantors" all guarantors for this patron will see this patron's current fines in the OPAC

  .. image:: /images/multipleguarantors.0110.png

-----

Bugs and problms:
-----------------

A. The "Add child" button has been renamed "Add guarantee" and is currently broken.  If you go to an adult's account and click on "Add guarantee," the adult will not be added as the guarantor for the child you're creating.  You still must search for the guarantor.  We expect this bug to be fixed soon.

  .. image:: /images/multipleguarantors.010a.png

B. As noted above, due to a bug, you *must* select a patron category when searching for a guarantor and the default search will be for "Adult" patrons.  If the patron you're searching for is not in the "Adult" category, you must select the category the patron you're searching for is a part of.  We expect this bug to be fixed soon.

  .. image:: /images/multipleguarantors.010b.png

C. You can no longer add a non-cardholder as a guarantor.  This is also something we expect to resolve soon.

  .. image:: /images/multipleguarantors.010c.png

D. The ability to add multiple guarantors to a patron account involved major changes to the database.  Because of this, all of the reports regarding guarantors will be broken after the upgrade and will need to be rewritten.
