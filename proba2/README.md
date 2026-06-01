## Proba-2 Science Archive Tutorials

This repository contains tutorial notebooks for the Proba-2 science archive.

### Requirements

`esa-p2sa` is a python module allowing users to work with P2SA data from within
a Jupyter Notebook.  The P2SA python module can be downloaded as a Wheel package from [here](https://p2sa.esac.esa.int/p2sa-py/esa_p2sa-1.1-py3-none-any.whl)
Once downloaded, you can install the package into your python enviroment with

```bash
pip install wheel
pip install  <wheel-P2SA-package.whl>
```

where `<wheel-P2SA-package.whl>` is the name of the downloaded file (most probably with the name `esa_p2sa-<version>-py3-none-any.whl`).
From here on, the P2SA TAP server can be accessed through this wrapper as described in the Jupyter Notebooks in this repository.

### Notebooks

The Jupyter notebook below provides a quick guide to the P2SA python module
functionality through several examples. At the moment, there are two notebooks
prepared:

-  The first one provides quick examples of how to retrieve data from P2SA
-  The second one is more specific and intended to provide examples of how to retrieve the Carrington Movies for a specific date.

In order to open the notebook locally, you can download them from the repository and run:

```
$ jupyter-notebook
```

The Jupyter Notebook will be opened in a browser. Note that the files downloaded from the notebook will be stored at the directory from where the notebook was launched.