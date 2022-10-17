.. Assig1 documentation master file, created by
   sphinx-quickstart on Tue Oct 11 15:27:08 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Assig1's documentation!
==================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Just reading Plato's Republic!

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
* :ref:`first function`

I used as example 'The Republic' written by Plato.
To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. py:function:: lumache.get_random_ingredients(kind=None)

   Return a list of random ingredients as strings.

   :param kind: Optional "kind" of ingredients.
   :type kind: list[str] or None
   :return: The ingredients list.
   :rtype: list[str]
 
The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.


.. py:exception:: lumache.InvalidKindError

   Raised if the kind is invalid.
   
   

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']


>>> def get_random_ingredients(kind=None):
>>> return ["shells", "gorgonzola", "parsley"]
hello


you can use the ``frequency_alphabet(filename,*args)`` function:

.. autofunction:: frequency_alphabet



.. autosummary::
   :toctree: generated

   lumache

