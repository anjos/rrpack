.. image:: https://travis-ci.org/anjos/rrpack.svg?branch=master
    :target: https://travis-ci.org/anjos/rrpack

#################################################################
Reproducible Logistic Regression on Fisher's Iris Flower Database
#################################################################

This bundle contains the code I used to generate the tables on the paper::

  @inproceedings{bob2012,
    author = {John Doe},
    title = {A Simple Solution to Iris Flower Classification},
    year = {2015},
    month = jun,
    booktitle = {Reproducible Research Conference, Rio de Janeiro, 2015},
    url = {http://example.com/path/to/my/article.pdf},
  }


We appreciate your citation in case you use results obtained directly or
indirectly via this software package.


Installation
------------

Run::

  $ python bootstrap_buildout.py
  $ ./bin/buildout

The tests on my paper were executed on a machine running Ubuntu 12.04, with
Python versions 2.6, 2.7, 3.3 and 3.4, providing the same results.


Running
-------

I have created a script that can run the source code reproducing all tables
from the above paper. Run it like so::

  $ ./bin/paper.py

The contents of each table in the paper should be printed one after the other.


Troubleshooting
---------------

You can run unit tests I have prepared like this::

  $ ./bin/nosetests

In case of problems, please get in touch with me `by e-mail
<mailto:john.doe@example.com>`_.

Licensing
---------

This work is licensed under the GPLv3_.


.. Here goes our links
.. _GPLv3: http://www.gnu.org/licenses/gpl-3.0.en.html
