# Mint Plus

An interactive, Jupyter notebook for viewing exported data from Mint.

[Mint](https://mint.com) is a wonderful tool, but in my opinion, it fails particularly around data visualizations for trends and properly displaying investment information.

I built this Jupyter notebook to view my earned and unearned income over time.

To use this notebook, you must create a folder within this repo named `data/` and put the following CSVs inside of it:
* An export of your Income trends from Mint, named `data/income.csv`
* An export of your Spending trends from Mint, named `data/spending.csv`
* An export of your Net Worth trends from Mint, named `data/net_worth.csv`

# Requirements
The following packages are required to run this Jupyter notebook:
* pandas
* seaborn
* jupyter

You may install these as a conda environment with the provided `environment.yml` file.

