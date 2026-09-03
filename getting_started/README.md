[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HPA-ESDC-ESA-INT/HPA-Jupyter-Notebooks/HEAD)

This section demonstrates HPA data access via three commonly used python packages, [pyvo](https://pyvo.readthedocs.io/), [astroquery](https://astroquery.readthedocs.io/en/latest/), and [sunpy](https://docs.sunpy.org/en/latest/).
Click the `Launch Binder` button above to launch the tutorials in your browser.

*Advantages of pyVO*

- No result size limit when launching synchronous queries
- Access to TAP Service attributes like `maxrec` and `hardlimit`

*Advantages of astroquery*

- Interface to TAP+ sercive developed by ESDC ([Salgado+ 2017](https://arxiv.org/pdf/1710.10509))
- Simpler interface to download data products compared to `pyVO`

*Advantags of sunpy*

- Most user-friendly interface