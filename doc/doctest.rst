.. vim: set fileencoding=utf-8 :
.. Andre Anjos <andre.dos.anjos@gmail.com>
.. Sat 16 Nov 20:52:58 2013

=====================
 Documentation Tests
=====================

It is prudent to make sure that bits of code you insert into your documentation
correspond to code that actually works. In the Python world, these are called
documentation tests or, for short, *doctests*. Sphinx supports doctests built
into the documentation.

Here is an example (the system tests the output or lack of is matched:

.. doctest::

   >>> from rr.analysis import CER
   >>> import numpy
   >>> a = numpy.array([0,1])
   >>> b = numpy.array([1,1])
   >>> CER(a, b)
   0.5

Notice that, in the generated HTML, you only see the Python code, properly
syntax-highlighted.
