# cw_constrain

[![PyPI version](https://badge.fury.io/py/cw-constrain.svg)](https://pypi.org/project/cw-constrain/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## Overview

`cw_constrain` is a Python package designed to provide tools and methods for constraining PBH abundance and the MSP hypothesis for the GeV excess using upper limits derived from continuous gravitational wave searches on real LIGO-Virgo-KAGRA data. It includes modules for analyzing GeV excess constraints, primordial black hole constraints, and shared utilities.

---

## Features

- Calculate constraints on MSP luminosity functions that explain the GeV excess using your own luminosity function, your own rotational frequency distribution and/or your own ellipticity distribution.
- Compute constraints on the fraction of dark matter that primordial black hole (PBHs) could compose using your own mass function or PBH formation model.
- Utility functions shared across modules for data processing
- Well-structured package suitable for scientific research and data analysis

---

## GeV excess constraints: how to use your own luminosity function

Please follow the tutorial in `tutorials/O4a_GeV_excess_tutorial.ipynb`

---

## Constraining PBH abundance with your own mass functions or formation models 

### PBH asteroid-mass constraints:


Please follow the tutorial in `tutorials/O4a_pbh_all_sky_tutorial.ipynb`

---

### PBH planetary-mass constraints:


Please follow the tutorial in `tutorials/O4a_light_pbh_tutorial.ipynb`

---


## Installation

You can install the package directly from PyPI:

```bash
pip install cw-constrain
```

And then in Python:

`import cw_constrain`


