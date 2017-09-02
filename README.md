## Overview

This is a more reader-friendly version of a project I worked on as part of my Udacity Machine Learning Nanodegree. The original project is available [here](https://github.com/jeremyjordan/machine-learning/tree/master/projects/customer_segments).

In this project, we'll look at purchasing data for clients of a wholesale distributor and attempt to use purchasing behavior to identify a way to predict what group each client belongs to. The characteristics of the grouping is unknown, we simply want to see if we can put similar observations (in this case, clients) into the same group. We'll then compare these predicted groupings to the true channels (Hotel/Restaurant/Cafe and Retail) each client belongs to.

Many companies today collect vast amounts of data on customers and clientele, and have a strong desire to understand the meaningful relationships hidden in their customer base. Being equipped with this information can assist a company engineer future products and services that best satisfy the demands or needs of their customers.

## Data

The customer segments data is included as a selection of 440 data points collected on data found from clients of a wholesale distributor in Lisbon, Portugal. More information can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

**Features**
1) `Fresh`: annual spending (m.u.) on fresh products (Continuous);
2) `Milk`: annual spending (m.u.) on milk products (Continuous);
3) `Grocery`: annual spending (m.u.) on grocery products (Continuous);
4) `Frozen`: annual spending (m.u.) on frozen products (Continuous);
5) `Detergents_Paper`: annual spending (m.u.) on detergents and paper products (Continuous);
6) `Delicatessen`: annual spending (m.u.) on and delicatessen products (Continuous);
7) `Channel`: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
8) `Region`: {Lisnon - 1, Oporto - 2, or Other - 3} (Nominal)

Note: (m.u.) is shorthand for *monetary units*.

For this project we'll attempt to **predict** which channel each client belongs to, so we won't look at this column until after we've segmented the data using clustering techniques.

### Instructions

This project requires Python 2.7. All of the libraries used in this project are included in the [Anaconda](http://continuum.io/downloads) distribution of Python, it is highly suggested that you use Anaconda to manage packages and environments for data science with Python.

When you're ready, fire up the notebook.

```bash
jupyter notebook customer_segments.ipynb
```
