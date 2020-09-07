# Mint Plus

An interactive, Jupyter notebook for viewing exported data from Mint.

[Mint](https://mint.com) is a wonderful tool, but in my opinion, it fails particularly around data visualizations for trends and properly displaying investment information.

I built this Jupyter notebook to view my earned and unearned income over time.

To use this notebook, you must put the following data exports from Mint inside the `data/` directory in this repo:
* your Income trends over time, named `data/income.csv`
* your Spending trends over time, named `data/spending.csv`
* your Net Worth trends over time, named `data/net_worth.csv`

# Requirements
Python 3.6+ is required to run this Jupyter notebook.
The following python packages are also required:
* pandas
* seaborn
* jupyter

You may install these as a conda environment with the provided `environment.yml` file.
