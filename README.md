# PyBer_Analysis
## Summary of Technical analysis
The purpose of this analysis is to show additional dimensions of information using the ridesharing data collected from .[2 csv files](https://github.com/tienl/PyBer_Analysis/tree/master/Resources). The files were loaded and processed using Python via Jupyter notebook and addons.  In the [PyBer-Challenge.ipynb](PyBer-Challenge.ipynb) file, it shows details of the analysis which used dataframes, formatting, arithematics and finally plotting the data into a graph.  
In the dataframe challenge_df3 shown below, we can see average fare per ride and per driver are the highest in rural city type, but total ride and drivers are less.  So if we calculate and look at the total fare collected from January through April urban city type still produce the highest aggregate fare collected.  The 3 different city types produced roughly the same rate over time of fare collection as indicated by the relatively flatness of the lines shown in totalfarebycity graph.  
### ![challenge_df3](/analysis/DF.png)
### ![totalfarebycity](/analysis/totalfarebycity.png)

## Challenges of the analysis process 
Some steps to produce the deliverables were described at a high level, a certain level of familiarity with python, pandas, and matplotlib, etc are expected.  Without the familiarity of these tools, one may need to have a resource such as the internet to learn and work through these challenges as needed.  A resampling technique had to be used to smooth out data in regular interval, which allowed us to plot the graph in uniform.  Without resampling the dataset would have gaps as shown below indicated by pivot table with NaN values.
### ![NaN](/analysis/NaN.png)

## Conclusion and additional thoughts
The data and analysis so far do not give us granular detail into additional patterns that may be useful.  Additional details such as weekdays versus weekends, seasons, rain patterns, or holidays.  If additional data can be obtained we can graph total fare over time but contrast the data between these factors on the X axis.  Another dimension that may be useful to learn is the cost of operation between different cities, if any.  If such data is available, we can deduce profitability of each city type operation.  
