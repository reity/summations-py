==========
summations
==========
Library to enumerate all natural number lists with a target sum.

.. image:: https://badge.fury.io/py/summations.svg
   :target: https://badge.fury.io/py/summations
   :alt: PyPI version and link.

Purpose
-------
This library allows programmers to create a generator for all the lists of natural numbers that add up to a target sum.

Package Installation and Usage
------------------------------
The package is available on PyPI::

    python -m pip install summations

The library can be imported in the usual way::

    import summations
    from summations import summations

Testing
-------

The library comes with a number of tests::

    nosetests

Examples
--------
An example of usage is provided  below::

    >>> from summations import summations
    >>> sorted(list(sum_len(5, 3)))
    [(0, 0, 5), (0, 1, 4), (0, 2, 3), (0, 3, 2), (0, 4, 1), (0, 5, 0),
     (1, 0, 4), (1, 1, 3), (1, 2, 2), (1, 3, 1), (1, 4, 0), (2, 0, 3),
     (2, 1, 2), (2, 2, 1), (2, 3, 0), (3, 0, 2), (3, 1, 1), (3, 2, 0),
     (4, 0, 1), (4, 1, 0), (5, 0, 0)]
