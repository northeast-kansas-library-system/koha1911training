Other changes
=============

Circulation
-----------

Check-in
^^^^^^^^

Checkin settings have moved

BEFORE:

  .. image:: /images/other.0010.png

AFTER:

  .. image:: /images/other.0020.png

|

  .. image:: /images/other.0021.png

-----

Searching
---------

Subtitle on checkins
^^^^^^^^^^^^^^^^^^^^

Can't show till after the upgrade because it will require running a process on the server after the upgrade

  .. image:: /images/other.0030.png


Limit to available items works better
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

There has been a bug affecting the "Limit to currently available items" search facet.  It is supposed to limit search results to show items where at least one copy is available for checkout.  Because of the bug, for some time "Limit to currently available items" has only been showing titles where 100% of the copies are available.

Can't show because the patch was back-ported to our existing system last week

  .. image:: /images/other.0040.png

|

  .. image:: /images/other.0041.png


Patrons
-------

Do not notify boxes gone
^^^^^^^^^^^^^^^^^^^^^^^^

All these checkboxes did was to un-check other boxes, so they have been removed from the table.

BEFORE:

  .. image:: /images/other.0050.png

AFTER:

  .. image:: /images/other.0051.png

Patron category/age warning
^^^^^^^^^^^^^^^^^^^^^^^^^^^

Most patron categories have age limitations.  There are some circumstances where a patrons' age may not match their patron category.  If the age and the patron category don't match, there will now be a warning to let staff know of the problem.

  .. image:: /images/other.0060.png


Attempting to delete a patron with reqeusts causes a warning message
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

It has been possible in the past to delete a patron that had unfilled requests.  Staff will now see a warning when they attempt to do this.

  .. image:: /images/other.0070.png
