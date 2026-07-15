## HPA - Jupyter Notebooks

This repository contains tutorial notebooks to illustrate the data access for different missions in the Heliophysics Archive.

You can launch an interactive Jupyter Lab session for all notebooks in this repository using [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HPA-ESDC-ESA-INT/HPA-Jupyter-Notebooks/HEAD)

### Requirements

The following requirements are necessary to run most/all notebooks in this repository.

#### Jupyter Notebook

The Jupyter Notebook App is a server-client application that allows editing and
running notebook documents via a web browser. The Notebook App can be executed
on a local desktop requiring no internet access or can be installed on a remote
server and accessed through the internet.

The Jupyter Notebook App is included in the Anaconda distribution so we recommend to install this product though it is not mandatory.
Anaconda can be downloaded from [here](https://www.anaconda.com/distribution/).

#### Node.js

`Node.js` can be downloaded from [here](https://nodejs.org/) and installed directly.  If you use `conda`, you can install `Node.js` with:

```bash
$ conda install -c conda-forge nodejs
```

If you use Homebrew on Mac OS X:

```bash
$ brew install node
```

#### python dependencies

See the `requirements.txt` file in this repository. You can install them all at once using

```python
python -m pip install -r requirements.txt
```
