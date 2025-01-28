.. continuous_int_course documentation master file, created by
   sphinx-quickstart on Tue Jan 28 15:10:39 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to cont_int_course's documentation!
=================================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Contents
--------

.. toctree::

   usage


Check out the :doc:`usage` section for further information.


Find minimum
----------------

To retrieve a list of random ingredients,
you can use the ``functionality.minimum()`` function:

.. py:function:: functionality.minimum(*args)

   Return a list of random ingredients as strings.

   :param args: The numbers from which to return the minimum.
   :type args: int, float
   :return: The minimum
   :rtype: int, float