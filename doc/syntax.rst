.. vim: set fileencoding=utf-8 :
.. Andre Anjos <andre.dos.anjos@gmail.com>
.. Sat 16 Nov 20:52:58 2013

=====================
 Syntax Highlighting
=====================

You can write blocks of code that will be properly syntax highlighted according
to the language set on the tag.

.. code-block:: python

   import os
   os.listdir(".")

For code blocks, you don't have to limit yourself to Python. You can also
document C/C++ code:

.. code-block:: c++

   #include <iostream>

   using namespace std;

   int main () {
       cout << "hello, world!" << end;
   }
