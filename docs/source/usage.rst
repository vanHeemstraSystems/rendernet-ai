Usage
=====

.. _installation:

Installation
------------

To use APPLICATION_NAME, first install it using pip:

.. code-block:: console

   (.venv) $ pip install PACKAGE_NAME

Getting Started
----------------

To retrieve a list of random ingredients,
you can use the ``PACKAGE_NAME.get_random_ingredients()`` function:

.. autofunction:: PACKAGE_NAME.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`PACKAGE_NAME.get_random_ingredients`
will raise an exception.

.. autoexception:: PACKAGE_NAME.InvalidKindError

For example:

>>> import PACKAGE_NAME
>>> PACKAGE_NAME.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']
