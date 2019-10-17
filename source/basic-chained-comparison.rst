Chained comparison operators
----------------------------

Some chained comparisons, like the one below, should be avoided. Notice the use of `and`?

Don't do this
^^^^^^^^^^^^^

.. code:: python

    x = 10
    y = 15
    z = 20

    if x <= y and y <= z:
        print('hi')

Do this
^^^^^^^

.. code:: python

    if x <= y <= z:
        print('hi')
