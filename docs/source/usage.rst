Usage
=====

.. _installation:

Accessing Saros
---------------

To get started working with Saros, join the Underworld Headquarters discord server!
From there, you can access him directly using the commands outlined below.

Creating Tasks
--------------

To retrieve a list of random ingredients,
you can use the ``saros.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`saros.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import saros
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

