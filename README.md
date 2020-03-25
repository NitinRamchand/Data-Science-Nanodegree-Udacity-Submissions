# Intro to Data Science Module Data Science Nanodegree - Looking into Airbnb Seattle Data - CRISP DM - Nitin Ramchand Lalwani

## Motivation of the Project

In this project I will go into detail analysis of some Airbnb Seattle Data and try and answer the following questions.

__1) Price trends:__ <br>
    In particular: <br>
    - Price flucations for each month during the year. <br>
    - Price fluctuations for the Jan 2016 to Jan 2017 different neighbourhoods in Seattle <br>
    - Price fluctuations for the different property types. <br>
    
__2)  Sentiment Analysis and Text Mining of the Reviews__ <br>
    In Particular: <br>
    - Identifying a quantified sentiment metric for an Airbnnb comment based on text mining <br>
    - What is the relationship between reviews and neihbourhoods <br>
    - What is the relationship between reviews and property types <br>
    
__3) Price prediction__ <br>
    Implemeting a Machine Learning algorithm to predict the price for new listings.
    
The answer to these questions, could help decision makers in targeting the right market for marketing campaings and increase in that way productivity.
   
## Libraries Used

The python libraries that I use are the following ones:

- Pandas
- Numpy
- NLTK
- Re
- Worldcloud
- Textblob
- Collections
- Operator
- Sklearn

## Files in the reposititory

The files that can be found in this repository are the following:

- Seattle.zip (insisde this zip file there are 3 csv files)
  - calendar.csv (This dataset is a collection of the all the listing reservations from the Jan2016 to Jan 2017 period including the price at which the listing was at)
  - reviews.csv (This dataset contains all the comments retrieved for the listings)
  - listings.csv (This dataset contains all the information about hosts and the property for a given listing)

- Intro_to_Data_Science_Final_Project.ipynb (This file is the jupyter notebook containing the detailed analysis of the work conducted in this project)
- Intro_to_Data_Science_Final_Project.html (This file is the html format containing the detailed analysis of the work conducted in this project)

## Summary of the results

__Price Trends__

We see that there is a clear fluctuation of the data where the summer months are the most expensive months in average and the winter months is the cheapest period (with a slight exception for the December month). Doing a quick search of the weather in Seattle for the different seasons, we see that the price fluctuations must be highly correlated with the weather forecast.

The neighbourhood with the highest average price is __Fairmount Park__

The property type with the highest average price is __Boat__

The property type with the lowest average price is __Dorm__

__Sentiment Analysis of the Reviews__

The neighbourhood with the best reviews is __Broadway__

Aside from Fairmount Park which has no reviews and therefore a polarity score of 0, the neighbourhood with the worst rewviews is __Roxhill__

__Price Prediction algorithm__

The most interesting algorithms are the AdaBoost, Decision Tree and the Nearest Neighboor Regressor. However if we have to make a decision at this stage we would keep the Decision Tree algorithm since it has the highest performance based on the time it takes to run the algorithm. In other words, the computing power required is much lower than the AdaBoost algorithm .

The decision tree algorithm has a R-squared value of 0.514143.


## Acknowledgments

https://data-science-blog.com/en/blog/2018/11/04/sentiment-analysis-using-python/

https://medium.com/@erikgreenj/k-neighbors-classifier-with-gridsearchcv-basics-3c445ddeb657
