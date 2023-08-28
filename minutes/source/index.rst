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

Sections
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

| The number of ``=`` or ``-`` must be greater or equal to that of the section text.  
  And the order of appearence becomes the order of section level.  
| In the example above,

* text surrounded by two ``=`` lines(v1) => h1
* one ``=`` line(v2) => h2
* text surrounded by two ``-`` lines(v3) => h3
* one ``-`` line(v4) => h4

Lists & Sublists
================================================

.. list and sublist

* list1

  * sublist1-1
  * sublist1-2

* list2

  * sublist2-1

    * subsublist2-1-1

Inline codes
================================================

| *Italic text* by surrounding with ``*``.
| **Bold text** by surrounding with ``**``.  
| ``Literal text`` by surrounding with \`.  

Hyper links
================================================

| To use hyper links, use back quotes and inequality signs.
| For example, a link to google would be something like this. ::

  \`This is a link to google v1 <https://google.com>\`__

`This is a link to google v1 <https://google.com>`__

If the url is too long or used often, give it a name and use it anywhere. ::
  
  .. _This is a link to google: https://google.com
  \`This is a link to google v2\`_

`This is a link to google v2`_

.. _This is a link to google v2: https://google.com
