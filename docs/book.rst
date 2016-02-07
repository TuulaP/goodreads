book
=======

.. automodule:: goodreads.book
   :members:
   :undoc-members:


Example

.. code:: python

   isbn="978-055-38-0371-6"
   book=gc.book(isbn=isbn)


After that it is possible to use the individual properties, which the module provides:

.. code:: python

   print book.title, book.authors[0], book.description, "\n"



