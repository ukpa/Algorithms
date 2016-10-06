.. algorithms documentation master file, created by
   sphinx-quickstart on Thu Oct  8 22:36:00 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Algorithms
==========

Algorithms is a library of algorithms and data structures implemented in Python.

The main purpose of this library is to be an educational tool. You probably
shouldn't use these in production, instead, opting for the optimized versions of
these algorithms that can be found else where.

You should totally check out the `docs`_ for implementation details, complexities
and further info.

Usage
-----

If you want to use the algorithms in your code it is as simple as:

::

    from algorithms.sorting import bubble_sort

    my_list = bubble_sort.sort(my_list)

Features
--------

- Pseudo code, algorithm complexities and futher info with each algorithm.
- Test coverage for each algorithm and data structure.
- Super sweet `documentation`_.

Installation:
-------------

Installation is as easy as:

::

    $ pip install algorithms


Tests:
------

Pytest is used as the main test runner and all Unit Tests can be run with:

::

    $ ./run_tests.py


Contributing:
-------------

Contributions are always welcome. Check out the contributing guidelines to get
started.

.. _`docs`: http://algorithms.readthedocs.org/en/latest/
.. _`documentation`: http://algorithms.readthedocs.org/en/latest/

Table of Contents:
------------------

.. toctree::
   :maxdepth: 2

   algorithms
