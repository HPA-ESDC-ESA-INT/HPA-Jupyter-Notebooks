<p align="center">
  <img src=".github/assets/banner.jpg" width="100%">
</p>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HPA-ESDC-ESA-INT/HPA-Jupyter-Notebooks/HEAD)

## ESA HelioPhysics Archive - Tutorial Notebooks

This repository contains tutorial notebooks demonstrating programmatic access to data from ESA's [Heliophysics Archive](https://hpa.esa.int) (HPA).

You can launch an interactive Jupyter Lab session for all notebooks in this repository using the `launch binder` button above.

## Requirements

To run the notebooks on your computer, you need to install different python packages. To do so, you can execute the following commands:

```shell
$ git clone https://github.com/HPA-ESDC-ESA-INT/HPA-Jupyter-Notebooks
$ cd HPA-Jupyter-Notebooks
$ python -m pip install -r requirements.txt
```

This will install the python packages listed in the `requirements.txt` file in your local python environment.

### Getting Started

The [Getting Started](getting_started/) directory contains information on the software prerequisites to run the tutorial notebooks as well as introductory notebooks on the usage of [PyVO](getting_started/01_data_access_with_pyvo.ipynb), [astroquery](getting_started/02_data_access_with_astroquery.ipynb) and [sunpy](getting_started/03_data_access_with_sunpy.ipynb) to access HPA data.

If you are already familiar with these topics, you can move straight on to the mission tutorials.

### Mission Tutorials

||
|:-------------------------:|
|<a href="proba2/"><img width="50%" src=".github/assets/proba2.png"></a> |
|[Proba-2](proba2/)|
