mediapack -- python materials repository
========================================

.. raw:: html

  <a href='https://github.com/cpplanes/mediapack/actions/workflows/python-package.yml'><img src='https://github.com/cpplanes/mediapack/actions/workflows/python-package.yml/badge.svg'/></a>
  <a href='https://coveralls.io/github/cpplanes/mediapack?branch=master'><img src='https://coveralls.io/repos/github/cpplanes/mediapack/badge.svg?branch=master'/></a>
  <a href="https://zenodo.org/doi/10.5281/zenodo.10932763"><img src="https://zenodo.org/badge/257514719.svg" alt="DOI"></a>



``mediapack`` is a Python package that provides a unified interface for materials and
media definitions in the context of computational acoustics. It was designed as a support
I/O library for the research projects of the Laboratory of Acoustics of Le Mans University (LAUM UMR CNRS 6613, Le Mans Université, Le Mans, France).

Licence and Citation
--------------------

``mediapack`` is distributed under the terms of the MIT license. If you use this package in your research, please cite it as follows:

  Mathieu G., & Olivier DAZEL. (2024). mediapack - Python Materials Repository. Zenodo. https://doi.org/10.5281/zenodo.10932763

Contributions
-------------

To contribute to the project, fork the repository, create a new branch, and submit a pull request.

Guidelines are as follow:

- The code should be PEP8 compliant.
- The code should be documented using the numpydoc format.
- The code should be tested using the pytest framework.
- The code should be covered by tests (ideally 100% coverage).
- The new code must respect existing conventions and architecture. The
  ``update_frequency`` method must be present and take the circular frequency as an input.
  It must update the properties of the class to match the new frequency. 


