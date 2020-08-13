.. vasppost documentation master file, created by
   sphinx-quickstart on Thu Aug 13 13:41:30 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to vasppost's documentation!
====================================
**vasppost** is used for analyzing the output of  VASP.

Basic Features
---------------
Band structure can be plotted simply by:

.. code-block:: python
   :linenos:

   VASP.py OUTCAR -band True -plt True or
   VASP.py vasprun.xml -band True -plt True

.. image:: image/band.png
   :scale: 30%
   :align: center

Contents:

.. toctree::
   :maxdepth: 2
   
   features
   tutorial

.. comment
.. Indices and tables
.. ==================

.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`

