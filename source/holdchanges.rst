Changes to requests
===================


Title vs item level request
---------------------------

A long standing bug has been fixed.

BEFORE:

1. Staff places title level request (note "Next available" in the "Details" column)

  .. image:: /images/holdchanges.1010.png

.. Hold placed for Jessica Frosty  FROSTX026 on SHAZAM - 0003008201376


2. When an item is "captured" to fill request, that specific item is tied to that specific request

  .. image:: /images/holdchanges.1020.png

.. Log in at ATCHISON and check in 0003008201376

3. The specific item is checked out to another patron before the request can be fille

  .. image:: /images/holdchanges.1031.png

3. Or the requested item is "Reverted" from "Waiting" to unfilled

  .. image:: /images/holdchanges.1032.png

.. Log back in at NEKLS and show that the specific item is now tied to that request

BEFORE:

4. Request can now **only** be filled by that specific Item

  .. image:: /images/holdchanges.1041.png

.. Revert the hold, note that the request is still tied to that item

AFTER:

4. Request reverts to a "Next available" request

  .. image:: /images/holdchanges.1042.png

.. Revert the hold, note that the request is still tied to that item

-----

Changes in check-in pop-ups
---------------------------

Item being returned
^^^^^^^^^^^^^^^^^^^

.. Check in STAN AND OLLIE at ATCHISON 0003008201338 - show pop-up

BEFORE: Only the transfer information appeared in the pop-up

  .. image:: /images/holdchanges.1110.png

AFTER: The transfer information plus any check-in messages appear in the pop-up

  .. image:: /images/holdchanges.1210.png

Item with a request at another library
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. Check in WIDOWS at ATCHISON 0003008201835 - Show pop-up

BEFORE:  Only the "Hold found" informaiton appeared in the pop-up

  .. image:: /images/holdchanges.1120.png

AFTER:  The "Hold found" information plus any check-in messages appear in the pop-up

  .. image:: /images/holdchanges.1220.png


Item with a request at this library
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. Switch to NEKLS and check in WIDOWS 0003008201835

BEFORE:  Only the "Hold found" informaiton appeared in the pop-up

  .. image:: /images/holdchanges.1130.png

AFTER:   The "Hold found" information plus any check-in messages appear in the pop-up

  .. image:: /images/holdchanges.1230.png

Ignoring any pop-up
^^^^^^^^^^^^^^^^^^^

BEFORE:  After you clear the pop-up, it's gone forever

  .. image:: /images/holdchanges.1140.png

AFTER:  Click on the "I" icon to get the pop-up back

  .. image:: /images/holdchanges.1240.png

-----

Too many holds vs Not holdable
------------------------------

BEFORE:

  .. image:: /images/holdchanges.1310.png

.. place request on -0003000050540- for FROSTX026

AFTER:

  .. image:: /images/holdchanges.1320.png

-----


Holds awaiting pickup now sorts by last name
--------------------------------------------

This has already been fixed on our live system, so no before picture is now possible

  .. image:: /images/holdchanges.1330.png

Staff can now edit purchase suggestions
---------------------------------------

This has already been fixed on our live system, so no before picture is now possible

  .. image:: /images/holdchanges.1340.png
