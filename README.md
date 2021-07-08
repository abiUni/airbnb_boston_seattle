# Comparison of Airbnb listings in Boston and Seattle

## Download the Data
The data used in this notebook is openly accessible on [insideairbnb.com](http://insideairbnb.com/get-the-data.html).
We use the following files in our analysis:
* listings.csv containing a description of all listings in a certain city
* calendar.csv containing the listing  price and availablity by date

Our dataset only includes the cities of Boston and Seattle and yearly calendar entries between 2016 and 2017

## Libraries
This notebook makes use of the following libraries:
* [Numpy](https://numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [matplotlib](https://matplotlib.org/)
* [seaborn](https://seaborn.pydata.org/)
* [datetime](https://docs.python.org/3/library/datetime.html)
* [re](https://docs.python.org/3/library/re.html)
* [math](https://docs.python.org/3/library/math.html)
* [itertools](https://docs.python.org/3/library/itertools.html) 
* [scipy](https://www.scipy.org/)

## Motivations
In this notebook we analyse the differences between Boston and Seattle in terms of listing prices, availability and neighborhoods in order to help users decide based on their budget which city to choose for their vacation.
We mainly provide answers to the following questions:
* How do the prices compare between Boston and Seattle?
* Which time of the year is availability highest in both cities?
* How do neighborhood and amenities affect price?

## Summary
* We found that mean listing prices in Boston were significantly higher than in Seattle 

![image info](./pictures/image.png)

* Availability is at its lowest around New year in Seattle and between August and October in Boston

![image info](./pictures/image.png)

* Neighbourhoods such as Back Bay, Fenway/Kenmore and Chinatown in Boston correlate most with listing price while Greenwood, North Beacon Hill and Maple Leaf in Seattle have the highest price correlation

![image info](./pictures/image.png)


## Acknowledgements
We would to acknowledge that analyses in this notebook were inspired by the [Kaggle notebook of Alexandra Deis](https://www.kaggle.com/aleksandradeis/airbnb-seattle-reservation-prices-analysis) and the [Medium article of Nadim Kawwa](https://medium.com/@nadimkawwa/boston-what-determines-airbnb-prices-d5bc670454b6), many thanks!
