.. -*- coding: utf-8 -*-

============
 Installing
============

The package is pure Python you easily install the `MDAnalysisData
package`_ from the Python Package Index (PyPi) with :program:`pip`:
	   
.. code-block:: bash

   pip install --upgrade MDAnalysisData

.. note:: The package itself is small and initially does not install
          any datasets. However, the :ref:`data directory
          <managing-data>` where datasets are cached can grow to many
          gigabytes.

.. _`MDAnalysisData package`:
   https://pypi.org/project/MDAnalysisData/

   
Installing from source
======================

Clone the repository with

.. code-block:: bash

   git clone https://github.com/MDAnalysis/MDAnalysisData.git

and install with :program:`pip`

.. code-block:: bash

   pip install MDAnalysisData/