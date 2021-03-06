# StateMint

[![PyPI](https://img.shields.io/pypi/v/StateMint.svg)](https://pypi.org/project/StateMint/)
[![License](https://img.shields.io/github/license/CameronDevine/StateMint.svg)](LICENSE)
[![Code of Conduct](https://img.shields.io/badge/contributor%20covenant-v1.4-blue.svg)](CODE_OF_CONDUCT.md)
[![status](http://jose.theoj.org/papers/7caec95b5db5c18d8a14cbc42fef7bb7/status.svg)](http://jose.theoj.org/papers/7caec95b5db5c18d8a14cbc42fef7bb7)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2633330.svg)](https://doi.org/10.5281/zenodo.2633330)

StateMint is a set of tools to symbolically determine the differential equation describing the dynamics of a system.
As inputs these tools take the elemental and constraint equations of a system.
A [tutorial](tutorial.md) is available which covers how to prepare equations for use with these tools.

### Mathematica

The Mathematica [package](mathematica) was the original implementation of this tool.
An [example](mathematica/Example.nb) of how to use the Mathematica package is provided.

### Python

A Python [package](python) was also created to provide an open source implementation of this tool using [SymPy](http://www.sympy.org).
This package allows anyone to use this tool on their own computer without having to obtain a license for proprietary software.
An [example](python/Example.ipynb) of how to use the Python package is also provided.

### Web Interface

A [web interface](web) is also available which uses the Python package as a backend.
This package allows anyone to use this tool without the need to install any software.
An example of this interface is running at [statemint.stmartin.edu](http://statemint.stmartin.edu).

## Contributors

- Cameron Devine, Dept. of Mechanical Engineering, University of Washington: Python Package and Web Interface
- [Rico Picone](http://ricopic.one), Dept. of Mechanical Engineering, St. Martin's University: Mathematica Package Maintenence
- Joseph Garbini, Dept. of Mechanical Engineering, University of Washington: Original Mathematica Package and Web Interface Terminology
- [Gavin Basuel](http://gavinbasuel.com), 1G Media & Design: Web Interface User Experience Design
