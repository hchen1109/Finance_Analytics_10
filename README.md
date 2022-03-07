# Finance Analytics No. 10: Crypto Clustering

#### This Jupyter notebook application clusters cryptocurrencies by their performance in different time periods. The results are plotted so that investors can see the performance visually.  Instead of basing proposal on only returns and volatility, the application includes other factors that might impact the crypto market — leading to better performance for the portfolio.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [python] (https://wiki.python.org/moin/FrontPage) - is an object-oriented, interpreted, and interactive programming language.

* [pathlib] (https://docs.python.org/3/library/pathlib.html) - This module offers classes representing filesystem paths with semantics appropriate for different operating systems.

* [matplotlib] (https://matplotlib.org) - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.

* [scikit-learn] (https://scikit-learn.org/stable/getting_started.html) - Scikit-learn is an open source machine learning library that supports supervised and unsupervised learning. It also provides various tools for model fitting, data preprocessing, model selection, model evaluation, and many other utilities.

* [hvPlot] (https://hvplot.holoviz.org/) - hvPlot provides an alternative for the static plotting API provided by Pandas and other libraries, with an interactive Bokeh-based plotting API that supports panning, zooming, hovering, and clickable/selectable legends.

---

## Installation Guide

Before running the application first install the following dependencies.

``` python
    conda activate dev
    jupyter lab
    conda list scikit-learn
    conda list hvplot
    pip install -U scikit-learn
    conda install -c pyviz hvplot
```
---

## Usage

To use the loan qualifier application simply clone the repository and run the following:

```python
  cd Github
  cd Finance_Analytics_10
  crypto_investments.ipynb
```

---

## Contributors

Brought to you by Haoyu Chen
