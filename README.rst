==========================================
Reference figures for the psy-maps package
==========================================

This repository is mainly designed for the continuous integration
of the psy-maps_ package. If you cloned the psy-maps repository,
get the identifier via through the get_ref_dir.py_ file::

    python tests/get_ref_dir.py -b

and the right path via::

    python tests/get_ref_dir.py

and in the cloned ``psy-maps`` repository, run::

    git submodule update --init `python tests/get_ref_dir.py`

.. _psy-maps: https://github.com/psyplot/psy-maps
.. _get_ref_dir.py: https://github.com/psyplot/psy-maps/blob/master/tests/get_ref_dir.py
