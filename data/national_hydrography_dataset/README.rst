Notes on Data
=============

This shapefile was provided by `Joey Thomas`_ at `TNRIS`_.  It's a shapefile
conversion of the National Hydrography Dataset (NHD) which is only available in
FileGDB (geodatabase format for ArcGIS).


Oddities
--------

* ``GNIS_ID`` fields are supposed to be zero-padded, eight digit numbers.  They
  aren't always.  For example, the Rio Grande has an ID of ``01385432`` and
  ``1385432``.
* ``GNIS_Name`` can't be relied on exclusively for unique identifiers.  There are
  multiple Red Rivers and Devil's Rivers within the state.  Their GNIS_ID can be
  used to determine which is unique.


.. _Joey Thomas: mailto:Joey.Thomas@twdb.texas.gov
.. _TNRIS: http://www.tnris.org/
