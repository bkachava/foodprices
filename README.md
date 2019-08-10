# Food Prices

## Background

By the year 2050, the world population is expected to grow to 9.7 billion, and
México will have 148 million of inhabitants.

As populations rise, urbanization increases and incomes grow, the agricultural
sector will be under mounting pressure to meet the demand for safe and nutritious
food.

Through this analysis, we will try to answer what is the participation of Mexico in 
the production of food, how Mexico compares in food prices with other countries and
how the production in Mexico has changed over the years.


## Data Analysis Process

Although the steps are listed in order, some of them were revisited 
more than once to refine the analysis.


### 1. Preparation

* Define a topic of interest: 
  
  -	What the World eats? 
  -	What is the participation of Mexico in the production of food? 
  -	How Mexico compares in food prices with other countries?

* Choose data sources: 
  
  -	The Food and Agriculture Organization (FAO) of the United Nations. A specialized agency that leads international efforts to defeat hunger. 
  -	National Institute of Statistics and Geography (INEGI). The institution responsible for performing censuses of Mexico and gathering statistical information useful for our project like prices of food.

* Choose datasets: 
  
  -	From FAO: Annual Population, Production, Food Supply, Trade, and Food Prices.
  -	From INEGI: Mexico City Food Prices.

* Define how to show Machine Learning in the context of our topic of interest: Price prediction


### 2. Data Exploration

* Data cleaning, exploration and transformation using `Microsoft Excel, Python Pandas and Python Matplotlib`.
 
 [Jupyter Notebooks](/Notebook)

* Create the files with information about North America Annual Population, Mexico’s Production, Mexico’s Food Supply, Mexico’s Trade with other countries of the world, and Mexico’s Food Prices in comparison with Canada, USA, other countries of America, and other countries of the world, to make visualizations using `Tableau`.
 
* Create the files with information about food prices to use them in the Machine Learning Algorithms.
 
 [Files](/Resources)


### 3. Machine Learning Implementation

* Select the algorithms for Price Prediction.
  -	FAO, small dataset – Deep Learning algorithm – `Long Short-Term Memory (LSTM)`
  -	INEGI, medium dataset – `Autoregressive Integrated Moving Average (ARIMA)`

* Analyze the time series and do the transformations required for making accurate predictions in the Machine Learning algorithms, using `Python Pandas and Python Matplotlib`.

* Implement the algorithms using `Scikit-Learn Machine Learning Library`. 

* Explore the results and make refinements using the suggested parameters e.g. GridSearchCV.

* Document the results.


### 4. Data Visualizations

* Publish datasets in `AWS Athena` to use them as data sources in `Tableau`.

![aws](/Dashboard/Images/aws.png)

* Design individual visualizations in Tableau and combine them in Tableau dashboards.

* Publish visualizations in Tableau Public to make them available for the final dashboard.


### 5. Dashboard

* Create a dashboard using HTML, CSS, and Bootstrap with a theme.

* Link the visualizations published in Tableau Public using HTML and JavaScript, to preserve the interactivity included in Tableau.

 [Tableau Files](/Tableau)

* Link the documentation with the Machine Learning results.

See the [dashboard](https://bkachava.github.io/foodprices/Dashboard/index.html).

![dash](/Dashboard/Images/dashboard.png)


