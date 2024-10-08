Pygeostat
====================

|pygeostatlogo| 

|integration_test| |docs| |PyPi| 

|Python36| |Python37| |Python38|

Introduction
+++++++++++++++++++++++

This is a Python package for geostatistical modeling. Pygeostat is aimed at preparing spatial data, scripting geostatistical workflows, modeling using tools developed at the Centre for Computational Geostatistics `(CCG) <http://www.ccgalberta.com>`_, and constructing visualizations to study spatial data, and geostatistical models. More information about installing and using pygeostat can be found in the `documentation <http://www.ccgalberta.com/pygeostat/welcome.html>`_.

For lessons on geostatiscts visit `Geostatistic Lessons <http://geostatisticslessons.com/>`_.


Contact:
+++++++++++++++++++
Refer to `www.ccgalberta.com <http://www.ccgalberta.com>`_

.. |pygeostatlogo| image:: http://www.ccgalberta.com/pygeostat/_images/pygeostat_logo.png

.. |integration_test| image:: https://github.com/CcgAlberta/pygeostat/workflows/IntegrationCheck/badge.svg?branch=master
    :alt: IntegrationTest
    :scale: 100%
    :target: https://github.com/CcgAlberta/pygeostat

.. |docs| image:: https://github.com/CcgAlberta/pygeostat/workflows/Documentation/badge.svg?branch=master
    :target: https://github.com/CcgAlberta/pygeostat
    :alt: Documentation Status
    :scale: 100%

.. |PyPi| image:: https://badge.fury.io/py/pygeostat.svg
    :target: https://badge.fury.io/py/pygeostat

.. |Python36| image:: https://img.shields.io/badge/python-3.6-blue.svg
    :target: https://www.python.org/downloads/release/python-360
    :alt: Python Version
    :scale: 100%

.. |Python37| image:: https://img.shields.io/badge/python-3.7-red.svg
    :target: https://www.python.org/downloads/release/python-370
    :alt: Python Version
    :scale: 100%

.. |Python38| image:: https://img.shields.io/badge/python-3.8-black.svg
    :target: https://www.python.org/downloads/release/python-380
    :alt: Python Version
    :scale: 100%


Using this fork:
+++++++++++++++++++

Installing

.. code-block:: python

    pip install git+https://github.com/attilalr/pygeostat-study.git


Using in Google Colab

.. code-block:: python

    try:
        import pygeostat as gs
    except:
        !pip3 install git+https://github.com/attilalr/pygeostat-study.git

        import pygeostat as gs

