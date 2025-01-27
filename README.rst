.. sec-begin-title

MESMER-OpenSCM Runner
=====================

.. sec-end-title

+-------------------+----------------+--------------+----------+------------+
| Repository health |    |CI CD|     |  |Coverage|  |  |Docs|  |  |Zenodo|  |
+-------------------+----------------+--------------+----------+------------+

+------+------------------+----------------+------------------+
| Pypi |  |PyPI Install|  |     |PyPI|     |  |PyPI Version|  |
+------+------------------+----------------+------------------+

+-----------------+----------------+---------------+-----------+
|   Other info    | |Contributors| | |Last Commit| | |License| |
+-----------------+----------------+---------------+-----------+

.. sec-begin-links

.. |CI CD| image:: https://github.com/MESMER-group/mesmer-openscmrunner/actions/workflows/ci-cd-workflow.yml/badge.svg
    :target: https://github.com/MESMER-group/mesmer-openscmrunner/actions/workflows/ci-cd-workflow.yml
.. |Coverage| image:: https://codecov.io/gh/MESMER-group/mesmer-openscmrunner/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/MESMER-group/mesmer-openscmrunner
.. |Docs| image:: https://readthedocs.org/projects/mesmer-openscm-runner/badge/?version=stable
    :target: https://mesmer-openscm-runner.readthedocs.io/en/stable/?badge=stable
.. |Zenodo| image:: https://zenodo.org/badge/DOI/10.5281/zenodo.5094379.svg
    :target: https://doi.org/10.5281/zenodo.5094379
.. |PyPI Install| image:: https://github.com/MESMER-group/mesmer-openscmrunner/workflows/Test%20PyPI%20install/badge.svg
    :target: https://github.com/MESMER-group/mesmer-openscmrunner/actions?query=workflow%3A%22Test+PyPI+install%22
.. |PyPI| image:: https://img.shields.io/pypi/pyversions/mesmer-openscmrunner.svg
    :target: https://pypi.org/project/mesmer-openscmrunner/
.. |PyPI Version| image:: https://img.shields.io/pypi/v/mesmer-openscmrunner.svg
    :target: https://pypi.org/project/mesmer-openscmrunner/
.. |Contributors| image:: https://img.shields.io/github/contributors/MESMER-group/mesmer-openscmrunner.svg
    :target: https://github.com/MESMER-group/mesmer-openscmrunner/graphs/contributors
.. |Last Commit| image:: https://img.shields.io/github/last-commit/MESMER-group/mesmer-openscmrunner.svg
    :target: https://github.com/MESMER-group/mesmer-openscmrunner/commits/master
.. |License| image:: https://img.shields.io/github/license/MESMER-group/mesmer-openscmrunner.svg
    :target: https://github.com/MESMER-group/mesmer-openscmrunner/blob/master/LICENSE

.. sec-end-links

.. sec-begin-shortsummary

Coupling between `MESMER <https://github.com/MESMER-group/mesmer>`_ and `OpenSCM-Runner <https://github.com/openscm/openscm-runner>`_.

.. sec-end-shortsummary

.. sec-begin-installation

Installation
------------

MESMER-OpemSCM Runner can be installed with pip: ``pip install mesmer-openscmrunner``.
For Windows users, note that we are having trouble with installation because installing
rasterio on Windows is non-trivial (see e.g. `here <https://rasterio.readthedocs.io/en/latest/installation.html>`_).

.. sec-end-installation

.. sec-begin-citing

Citing MESMER-OpenSCM Runner
----------------------------

Scientific publications using MESMER-OpemSCM Runner should cite the following publications alongside the appropriate global-mean temperature emulator publications:

  Beusch, L., Nicholls, Z., Gudmundsson, L., Hauser, M., Meinshausen M., and Seneviratne,
  S. I.: From emission scenarios to spatially resolved projections with a chain of
  computationally efficient emulators: MAGICC (v 7.5.1) - MESMER (v 0.8.1) coupling,
  Geosci. Model Dev. Discuss. [preprint], https://doi.org/10.5194/gmd-2021-252, in review,
  2021.

  Beusch, L., Gudmundsson, L., and Seneviratne, S. I.: Emulating Earth system model
  temperatures with MESMER: from global mean temperature trajectories to grid-point-level
  realizations on land, Earth Syst. Dynam., 11, 139–159,
  https://doi.org/10.5194/esd-11-139-2020, 2020.

.. sec-end-citing

.. sec-begin-license

License
-------

Copyright (c) 2021 MESMER-OpenSCM Runner contributors, listed in AUTHORS, and ETH Zurich.

MESMER-OpenSCM Runner is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License (see `LICENSE <https://github.com/MESMER-group/mesmer-openscmrunner/blob/master/LICENSE>`_), or
(at your option) any later version.

MESMER-OpenSCM Runner is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.

The full list of code contributors can be found in AUTHORS or at
`github.com/MESMER-group/mesmer-openscmrunner/graphs/contributors <https://github.com/MESMER-group/mesmer-openscmrunner/graphs/contributors>`_.

.. sec-end-license
