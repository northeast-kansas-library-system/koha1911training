Changes to requests
===================


Title vs item level request
---------------------------

A long standing bug has been fixed.

BEFORE:

Staff places title level request

.. Hold placed for Jessica Frosty on SHAZAM - 0003008201376

Item is "captured" to fill request and that specific item is tied to that request

.. Log in at ATCHISON and check in 0003008201376

The specific item is checked out to another patron before the request can be filled

.. Log back in at NEKLS and show that the specific item is now tied to that request

Request can now **only** be filled by that specific Item

.. Revert the hold, note that the request is still tied to that item


AFTER:

Staff places title level request

.. Hold placed for Jessica Frosty on SHAZAM - 0003008201376

Item is "captured" to fill request and that specific item is tied to that request

.. Log in at ATCHISON and check in 0003008201376

The specific item is checked out to another patron before the request can be filled

.. Log back in at NEKLS and show that the specific item is now tied to that request

Request can now **only** be filled by that specific Item

.. Revert the hold, note that the request is still tied to that item


Changes in hold pop-up
----------------------

BEFORE:

Item being returned

.. Check in STAN AND OLLIE at ATCHISON 0003008201338 - show pop-up

Item with a request at another library

.. Check in WIDOWS at ATCHISON 0003008201835 - Show pop-up

Item with a request at this library

.. Switch to NEKLS and check in WIDOWS 0003008201835

AFTER:

Item being returned

.. Check in STAN AND OLLIE at ATCHISON 0003008201338 - show pop-up

Item with a request at another library

.. Check in WIDOWS at ATCHISON 0003008201835 - Show pop-up

Item with a request at this library

.. Switch to NEKLS and check in WIDOWS 0003008201835
