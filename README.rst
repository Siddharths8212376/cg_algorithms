=============
cg_algorithms
=============


.. .. image:: https://img.shields.io/pypi/v/cg_algorithms.svg
..         :target: https://pypi.python.org/pypi/cg_algorithms

.. .. image:: https://img.shields.io/travis/Siddharths8212376/cg_algorithms.svg
..         :target: https://travis-ci.org/Siddharths8212376/cg_algorithms

.. .. image:: https://readthedocs.org/projects/cg-algorithms/badge/?version=latest
..         :target: https://cg-algorithms.readthedocs.io/en/latest/?badge=latest
..         :alt: Documentation Status

Now Available on test.PYPI !!
-----------------------------

.. code-block:: python

    pip install -i https://test.pypi.org/simple/ cg-algorithms
    

This project contains ready to use computer graphics algorithms for easier workflow and better productivity,
implemented using opengl-python.


* Free software: MIT license
* Documentation: https://cg-algorithms.readthedocs.io.


Features
--------

* The given repository contains ready to use implementation of major computer graphics algorithms for easier workflow and better productivity.

Installation
------------
With Python Package Manager ``pip``:

.. code-block:: python

    pip install -i https://test.pypi.org/simple/ cg-algorithms

Basic Usage:
------------

.. code-block:: python

    import cg_algorithms

For importing the circle algorithms:
------------------------------------


.. code-block:: python

    # for importing circle algorithms
    from cg_algorithms import circle_algorithms
    
    # for importing line algorithms
    from cg_algorithms import line_algorithm

Creating a circle object:
-------------------------

.. code-block:: python

    new_circle = circle_algorithms(<radius>, <x_centre>, <y_centre>)

Calling the function to draw the circle using Bresenham's algorithm:
--------------------------------------------------------------------

.. code-block:: python

    new_circle.bresenham_circle()

Credits:
--------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage

Sources:
--------
View My Project at: https://test.pypi.org/project/cg-algorithms/0.1.5/

Main Site: https://test.pypi.org/project/cg-algorithms/

Thanking Notes:
---------------
Thanking all the contributors for their contributions.

Algorithm's Library and previous builds available at:
-----------------------------------------------------

https://github.com/Siddharths8212376/PyOpenGL-for-Windows/tree/master/ALGORITHMS_LIBRARY
