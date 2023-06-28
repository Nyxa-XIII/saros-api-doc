Usage
#####

.. _installation:

Accessing Saros
===============

To get started working with Saros, join the `Underworld Headquarters <https://discord.com/invite/K6MEgNj4HZ/>`_ discord server!
From there, you can access him directly using the commands outlined below.

Task Module
===========

Add Tasks
---------

Add tasks does...
"""""""""""""""""

code-block:: text
    !add tasks -> Go to the store!


Clear Completed Tasks
---------------------

Clear tasks
-----------

Complete Suggestions
--------------------

Complete Tasks
--------------

Delete Tasks
------------

List Suggestions
----------------

List Tasks
----------


To view your current list of tasks, ,
you can use the ``saros.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`saros.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

code-block:: text
   import saros

   lumache.get_random_ingredients()

   ['shells', 'gorgonzola', 'parsley']

