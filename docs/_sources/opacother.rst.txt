Other OPAC changes
==================


Floating toolbar
----------------

The control bar for the OPAC search results now floats

BEFORE:

  .. image:: /images/opacother.0010.png

AFTER:

  .. image:: /images/opacother.0020.png


Locate on device
----------------

On a title's details page in the OPAC, you can click on a new button called "Send to device" that will generate a QR code for the title's page in the OPAC.  You can then scan the code with your phone and the record will open on your phone's browser.

  .. image:: /images/opacother.0030.png

|

  .. image:: /images/opacother.0040.png

Editions problem fixed
----------------------

The OPAC uses the ISBN numbers for an item and a FRBRization service to add links to different editions of the same work to the "Editions" tab in the OPAC.  In the past, if a title had multiple ISBNs on the same title, the editions were grouped by ISBN, causing an title to show up on its own "Editions" tab.  The titles are now configured to group on biblionumber, so fewer titles should appear on the "Editions" tab and none of them should refer back to the title you are currently looking at.

  .. image:: /images/opacother.0050.png



-----

Video on this topic:
--------------------

Watch a YouTube video about patron changes.

.. only:: html

  .. raw:: html

      <div style="position:relative;padding-top:50%;">
        <iframe src="https://www.youtube.com/embed/-wb-EiB5ipk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;"></iframe>
      </div>

.. only:: latex

   https://youtu.be/-wb-EiB5ipk

-----
