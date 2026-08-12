


To install the labs, you will need to have python installed, preferably through [anaconda](https://www.anaconda.com/download/).

You can then clone this reposiroty. From a command line, run

```
git clone https://github.com/AlainPlattner/gpgLabs.git
```

Then `cd` into `gpgLabs`

```
cd gpgLabs
```

To setup your software environment, we recommend you use the provided conda environment

```
conda env create -f environment.yml
conda activate geosci-labs
```

The first time after activating geosci-labs, you need to run the following:

```
conda install -y -c conda-forge openssl=3.5.5
```

You can then launch Jupyter
```
jupyter notebook
```

Jupyter will then launch in your web-browser.

## Running the notebooks

Each cell of code can be run with `shift + enter` or you can run the entire notebook by selecting `cell`, `Run All` in the toolbar.

![cell-run-all](https://em.geosci.xyz/_images/run_all_cells.png)

For more information on running Jupyter notebooks, see the [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/)

## Issues

If you run into problems or bugs, please let us know by [creating an issue](https://github.com/geoscixyz/gpgLabs/issues/new) in this repository.

## For Contributors

We are glad you are interested in contributing! 

This repo tracks [geosci-labs](https://github.com/geoscixyz/geosci-labs). To contribute code, ideas or bug-fixes, please head over to the [geosci-labs](https://github.com/geoscixyz/geosci-labs) repository. 




