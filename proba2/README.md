[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HPA-ESDC-ESA-INT/HPA-Jupyter-Notebooks/HEAD)

## Proba-2 Science Archive Tutorials

This repository contains tutorial notebooks for the [Proba-2 Science Archive](https://p2sa.esac.esa.int/p2sa/). 

The TAP URL of the P2SA is

```
https://p2sa.esac.esa.int/p2sa-sl-tap/tap
```

### Requirements

Standard requirements, see `requirements.txt` in the root of this repository.

### Notebooks

The following notebooks are available:

-  [pyP2SA.ipynb](https://github.com/HPA-ESDC-ESA-INT/HPA-Jupyter-Notebooks/blob/main/proba2/pyP2SA.ipynb) - Access observation metadata in the P2SA via TAP
-  [pyP2SA-carrington.ipynb](https://github.com/HPA-ESDC-ESA-INT/HPA-Jupyter-Notebooks/blob/main/proba2/pyP2SA-carrington.ipynb) - Download and display a Carrington movie from the P2SA

You can run the notebooks online using the "launch binder" button above. In order to open the notebook locally, you can download them from the repository and run:

```
$ jupyter-notebook
```

The Jupyter Notebook will be opened in a browser. Note that the files downloaded from the notebook will be stored at the directory from where the notebook was launched.
