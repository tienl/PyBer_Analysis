# PyBer Analysis

In this repository I demonstrated skills using python with matplotlib library for charting to performe analysis and charting for presentation.

## Background and Results
### Background  
The purpose of this analysis is to demonstrate additional dimensions of information using the ridesharing data collected from .[2 csv files](https://github.com/tienl/PyBer_Analysis/tree/master/Resources). The files were loaded and processed using Python via Jupyter notebook and additional libraries.  In the [PyBer-Challenge.ipynb](PyBer-Challenge.ipynb) file, it shows steps of the analysis which included multiple processing of data into dataframes, formatting, and arithematics on the data.  Finally, the post processed data is produced into a graph.  

### Results 
In the dataframe challenge_df3 shown below, we can see "average fare per ride" and "average fare per driver" are the highest in rural city type, but amount of rides and drivers are less in rural city.  If we calculate and look at the total fare collected from January through April, rural city type produced the least amount of aggregate fare collected.  By contrast, urban city type produced the highest aggregate fare.  Additionally, the 3 different city types produce roughly the same rate over time of fare collected.  This is indicated by the relatively flatness of the lines shown in totalfarebycity graph.  
### ![challenge_df3](/analysis/DF.png)
### ![totalfarebycity](/analysis/totalfarebycity.png)

## Challenges Encountered and Overcome
Some steps to produce the deliverables were described at a high level, a certain level of familiarity with python, pandas, and matplotlib, etc are expected.  Without the familiarity of these tools, one may needs additional resource such as the internet to help work through the programing to manipulate the data as needed.  Additionally, a resampling technique was used to smooth out data into regular interval, which allow the plot of a graph in into continuous lines.  Without resampling the dataset has natrual gaps with existing index, a snippet of the table is shown below.  The NaN indicates a void of data for the given time index.
### ![NaN](/analysis/NaN.png)

## Recommendations and Next Steps
The data and analysis so far do not give us granular detail into additional patterns that may be useful.  Additional details such as weekdays versus weekends, seasons, rain patterns, or holidays.  If additional data can be obtained we can graph total fare over time but contrast the data between these factors on the X axis.  Another dimension that may be useful to learn is the cost of operation between different cities, if any.  If such data is available, we can deduce profitability of each city type operation.  
