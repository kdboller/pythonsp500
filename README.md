# pythonsp500

This repository contains the Jupyter notebook with full code for the "Python for Finance:  Stock Portfolio Analyses" post, as well as an excel file which is initially read in as a sample portfolio.

---

## Relevant posts where you can find the tutorial

1. Medium: https://towardsdatascience.com/python-for-finance-stock-portfolio-analyses-6da4c3e61054
2. Personal blog:  https://kdboller.github.io/2018/03/04/scaling-financial-insights-with-python.html

## Getting set up

1. Clone this repository:  ``git clone https://github.com/kdboller/pythonsp500``; or 
2. Hit 'Clone or download' on the main repo page in order to grab the Jupyter notebook and the sample excel file; or
3. The notebook itself can be downloaded on nbviewer; link is [here](http://nbviewer.jupyter.org/github/kdboller/pythonsp500/blob/a7066d998ff046c3cc8b26ece3b0efdf00959d57/Investment%20Portfolio%20Python%20Notebook_03_2018_blog%20example.ipynb).

## Note on Anaconda distribution

I highly recommend that you download the [Anaconda distribution](https://www.anaconda.com/download/).  You can also run the notebook without Anaconda using ``pip`` to install the required packages, however Anaconda is the industry standard for data science.

For any packages not distributed under Anaconda, e.g., the Yahoo Finance package fix, you can do the following directly in a cell within the notebook:
``!pip install [name of package]``

## Future additions

1. Add an environment.yml file in order to allow for the creation and usage of a new conda environment.
