# pydata-simpsons

A collection of jupyter notebooks and a utility python script created for the PyData Seattle 2017 tutorial on [Unevenly spaced time series analysis of The Simpsons in Pandas](https://pydata.org/seattle2017/schedule/presentation/104/).

Notebooks:
* **pydata-tutorial-simpsons-ANSWERS.ipynb**: version with answers included
* **pydata-tutorial-simpsons-CLEAN.ipynb**: version with answers omitted (recommended for people who want to do the exercises) 
* **pydata-tutorial-simpsons-SESSION.ipynb**: version used during tutorial session (annotated afterward)
* **pydata-tutorial-simpsons-data-cleaning.ipynb**: notebook used to clean up the data (incomplete)

Python script with utilty functions used in the notebooks:
* **pydata_simpsons.py**

There are also HTML versions of all the notebooks, provided for the benefit of anyone not able to run the notebooks.

Requirements:
* Latest versions of [pandas](http://pandas.pydata.org/) and [jupyter notebook](http://jupyter.org/) (recommended: use [Anaconda](https://www.continuum.io/downloads))
* data.world Python SDK 
  * `conda install -c conda-forge datadotworld-py` (if using Anaconda)
  * `pip install git+git://github.com/datadotworld/data.world-py.git` (if not using Anaconda)
* a data.world account and an API key (via the [data.world Advanced Settings page](https://data.world/settings/advanced))
