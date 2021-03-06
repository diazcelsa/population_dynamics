# Prediction of internal migrations
## Internal migration analysis of the city of Madrid before, during and after the economic crisis of 2008

The internal migration analysis between districts has been performed between the years 2004 and 2017.

The data sources are:

* Data Bank from the City of Madrid
* Spanish National Institute of Statistics (INE)
* Inside Airbnb
* Idealista

Previous pre-processing of the data from the City of Madrid is detailed [here](https://github.com/diazcelsa/visualizations).

The goal is to build a linear model to predict the number of internal migrations between districts over these years.

It was observed that the factors that are correlated with the number of migrations (with a confidence of 95%) vary depending on the historical period. Therefore, the analysis was performed separately for the years before the crises, during the crisis and after the crisis.

Additionally, the migrations over time are also studied aggregating districts by the average net income level and their situation (centre of the city or in the suburbs).

If you want to read more about the results, have a look at this [blog post](http://www.ourdataourinsights.com/population_dynamics_crisis.html).

#### Relative migrations flow between 2004 and 2017
![Relative migrations flow between 2004 and 2017](img/relative_migrations.png?raw=true "Title")
