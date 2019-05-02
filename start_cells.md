# PmagPy Command Line Version

by Lisa Tauxe, Lori Jonestrask, Nick Swanson-Hysell and Nick Jarboe

This notebook demonstrates the use of **PmagPy** command line scripts.  Additional background and documentation can be found  in the [**PmagPy** Cookbook](http://earthref.org/PmagPy/cookbook).


## What is **PmagPy**?

**PmagPy** is a software package for analyzing paleomagnetic and rock magnetic data using Python. If you need to install Python and PmagPy locally, follow [the install instructions](https://earthref.org/PmagPy/cookbook/#getting_python). This notebook demonstrates the use of **PmagPy** functions on the command line. For examples of how to use PmagPy scripts in a Python environment, see the static version of [**PmagPy.ipynb**](http://pmagpy.github.io/PmagPy.html) or if you are running jupyter notebook, you can open it locally.

## What are paleomagnetism and rock magnetism?

For information on the science of paleomagnetism and rock magnetism, see [Essentials of Paleomagnetism](https://earthref.org/MagIC/books/Tauxe/Essentials/).


## Running this notebook

You are currently looking at static html, but you may want to run this notebook interactively. To do so, you'll need to first install Python and PmagPy (see [the Cookbook](https://earthref.org/PmagPy/cookbook/#getting_python) for install instructions).  You can then launch the notebook from your command line (see [more details here](https://earthref.org/PmagPy/cookbook/#notebook_quickstart)).


## Get started
- These examples are meant to function from within the PmagPy-data directory and calls are relative to that (PmagPy directory for developers).
- To specify a working directory, many programs have the command line argument -WD.








# Chunks for use in the non-cli notebooks


## Guide to PmagPy

The notebook is one of a series of notebooks that demonstrate the functionality of PmagPy. The other notebooks are:

- [PmagPy_introduction.ipynb](https://pmagpy.github.io/PmagPy_introduction.html) This notebook introduces PmagPy and lists the functions that are demonstrated in the other notebooks.
- [PmagPy_calculations.ipynb](https://pmagpy.github.io/PmagPy_calculations.html) This notebook demonstrates many of the PmagPy calculation functions such as those that rotate directions, return statistical parameters, and simulate data from specified distributions.
- [PmagPy_plots_analysis.ipynb](https://pmagpy.github.io/PmagPy_plots_analysis.html) This notebook demonstrates PmagPy functions that can be used to visualize data as well as those that conduct statistical tests that have associated visualizations.
- [PmagPy_MagIC.ipynb](https://pmagpy.github.io/PmagPy_MagIC.html) This notebook demonstrates how PmagPy can be used to read and write data to and from the MagIC database format including conversion from many individual lab measurement file formats.


## Get started

To use the functions in this notebook, we have to   import the **PmagPy** modules **pmagplotlib**, **pmag** and **ipmag** and some other handy functions.  This is done in the following code.

In order to access the example data, these examples are meant to be run in the PmagPy-data directory (PmagPy directory for developers).


## Running this notebook

You are currently looking at static html, but you may want to run this notebook interactively. To do so, you'll need to first install Python and PmagPy (see [the Cookbook](https://earthref.org/PmagPy/cookbook/#getting_python) for install instructions).  You can then launch the notebook from your command line (see [more details here](https://earthref.org/PmagPy/cookbook/#notebook_quickstart)).
