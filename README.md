# Boston Airbnb project

In this repo the boston airbnb data will be analysed using public data from kaggle.

## Files used in repository:

### boston_airbnb.ipynb

This is a jupyter notebook which answers questions regarding the boston airbnb data obtained from kaggle (https://www.kaggle.com/airbnb/boston)

### listing.csv

A csv file containing information about airbnb listings in boston

### map

A folder containing the geographical data on boston. This is used to produce the chloropleth which was produced in `boston_airbnb.ipynb`.

## Motivation

 Airbnb provides a service which helps to match people who are looking to rent with people who are looking to lend. Airbnb uses a fee for host model as their main source of income where a service fee is charged to a visitor and a renting fee is extracted from the host.

This notebook will try to focus on how to maximise the price of a given accomodation and also look into how to maximise value for potential visitors.

__Questions to be answered__

* __Which rooms are the most profitable to rent out?__
* __Which locations offer the best bang for buck in terms of renting?__
* __Which factors affect pricing the most?__ 

## Summary

From this notebook we have answered all the questions and have attained the following actionable information from each of the respective questions:

* __Which rooms are the most profitable to rent out?__

The most profitable rooms (in terms of revenue per month) to rent out are entire homes/apartments.

* __Which locations offer the best bang for buck in terms of renting?__

The best area to rent out in terms of rating per dollar is Hyde Park. With most of the best bang for buck locations being in the south of boston.

* __Which factors affect pricing the most?__ 

The most important features in determining the pricing of an accomodation by far are the number of bedrooms. Furthermore whats interesting is that most of the features such are largely assocated with the overall size of the accomodation and it's ability to comfortably facilitate more guests.

## Dependencies

The following depencies for the project are as follows:
* geopandas
* adjustText
* pandas
* numpy
* matplotlib
* scikit-learn
* seaborn

To install all the dependencies run the following command:

pip3 install geopandas adjustText pandas numpy matplotlib scikit-learn seaborn

## Acknowledgements

The dataset for the information about the airbnb listings in boston was obtained from https://www.kaggle.com/airbnb/boston.
The geographical data used to create the chloropleth in the `boston_aitbnb` notebook was obtained from https://data.boston.gov/dataset/city-of-boston-boundary.

The additional resources which were used in the notebook are as follows:
* https://www.programmersought.com/article/27117592996/
* https://xgboost.readthedocs.io/en/latest/python/python_api.html




