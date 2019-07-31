## Movie Recommendation System

### Description

This project, employs several supervised algorithms to accurately model individuals' income using data collected from the 1994 U.S. Census. It then chooses the best candidate algorithm from preliminary results and further optimizes it to best model the data. The goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000. This sort of task can arise in a non-profit setting, where organizations survive on donations. Understanding an individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with. While it can be difficult to determine an individual's general income bracket directly from public sources, this project shows that we can infer this value from other publically available features.

### Install

This project implemented using **Python 3.7** and the following Python libraries:

- [Jupyter Notebook (IPython) 4.10.0](https://ipython.org/)
- [NumPy 1.16.4](http://www.numpy.org/)
- [Pandas 0.24.2](http://pandas.pydata.org/)
- [matplotlib 2.2.4](http://matplotlib.org/)
- [scikit-learn 0.17](http://scikit-learn.org/stable/)

### Code

Template code is provided in the `market-research.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `housing.csv` dataset file to complete your work.

### Run

In a terminal or command window, navigate to the top-level project directory `market-research/` (that contains this README) and run one of the following commands:

```bash
ipython notebook market-research.ipynb
```  
or
```bash
jupyter notebook market-research.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data
The data we'll be using comes from the wonderful [MovieLens](https://movielens.org/) [user rating dataset](https://grouplens.org/datasets/movielens/). We'll be looking at individual movie ratings later in the notebook, but let us start with how ratings of genres compare to each other.
