.. Sphinx first project documentation master file, created by
   sphinx-quickstart on Sun Aug 27 02:57:42 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
   
================================================
Sphinx first project
================================================

Edit data: 2023-08-27

.. toctree::
   :maxdepth: 2
   :caption: Contents:

How to write Sections
================================================

When writing header text(htags in html), use multiple ``=`` or ``-`` characters.::

   ================================================
   Section text v1
   ================================================

   Section text v2
   ================================================

   ------------------------------------------------
   Sevtion text v3
   ------------------------------------------------

   Section text v4
   ------------------------------------------------

The result of above looks like this.

*****(result start)*****

================================================
Section text v1
================================================

Section text v2
================================================

------------------------------------------------
Sevtion text v3
------------------------------------------------

Section text v4
------------------------------------------------

*****(result end)*****

| The number of ``=`` or ``-`` must be greater or equal to that of the section text.  
  And the order of appearence becomes the order of section level.  
| In the example above,

* text surrounded by two ``=`` lines(v1) => h1
* one ``=`` line(v2) => h2
* text surrounded by two ``-`` lines(v3) => h3
* one ``-`` line(v4) => h4

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

