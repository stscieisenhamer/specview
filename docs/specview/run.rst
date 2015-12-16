.. _specview-run:

Running specview
==================================

``specview`` is both a standalone application as well as providing an
application interface (API) to use from other Python scripts or from
an iPython shell.

.. _specview-run-app:

Run as an application
---------------------

The easiest use of specview is to run from the command line as::

    sview

This will bring up the basic specview window

.. image:: /_static/sview_init_screenshot.png
  :width: 800px
  :alt: specview opening window


.. _specview-run-api:

Invoke specview from Python
---------------------------

``specview`` may be invoked from a Python script as follows::

  >>> import specview.main import SView
  >>> sv = SView()
