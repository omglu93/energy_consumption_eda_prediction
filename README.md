# Energy consumption - Time Series forecasting

The goal of this notebook is to provide some interesting insights into the consumption of a regional transmission network and macro consumption trends on a multi-state level.

All the available data is straightforward with no missing values and limited space for feature-engineering. As such, the focus will be on creating features based on the time-series column to provide additional information to the algorithm.  

This was a fun and short project where I could experiment with different time-series options, lag functions and the rolling values method.  

The complete notebook can be accessed [here](https://nbviewer.jupyter.org/github/omglu93/energy_consumption_eda_prediction/blob/master/energy-consumption-eda-prediction.ipynb).

![los](/images/img1.jpg)


# Dataset

The data is provided by www.pjm.com

- 2 features/columns
- 145,000 rows of data


# Requirements
- Python 2.7 or Python 3.6
- Jupyter Notebook

# License
MIT. See the LICENSE file for the copyright notice.

# References:

1. https://arxiv.org/pdf/1603.02754v1.pdf
2. https://en.wikipedia.org/wiki/Regional_transmission_organization_(North_America)
3. https://www.pjm.com/about-pjm.aspx
