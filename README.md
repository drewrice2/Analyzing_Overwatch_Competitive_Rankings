# **Analyzing Overwatch Competitive Rankings**
### An analysis of r/CompetitiveOverwatch!


The goal of this project was to analyze the distribution of players' ranks after opening day of Overwatch's competitive mode. The players polled were from reddit.com/r/CompetitiveOverwatch using a Google Form. The initial response rate was high, with a few thousand responses coming in during the first few hours, so a quick analysis method was needed. I threw the data (included in the repo) into a notebook, cleaned the data, and plotted the distribution.

A Jupyter Notebook was the best choice for the job to easily generate and read summary statistics. Graphing on new data was very straightforward too. Every half hour or so, I reran the script on the new data in order to update the notebook. The data cleaning was necessary due to some troll responses such as string data and values outside of the expected range. After an initial cleaning, I limited the data by chopping off the first and last 5%. Finally, I updated the repo after each run of the script in order to share the info with reddit.

Here is the distribution, as seen in the Python notebook.

![alt tag](https://github.com/drewrice2/Analyzing-Overwatch-Competitive-Rankings/blob/master/Distribution.png)

The data is available from this repo in .csv format. **WARNING:** some of the troll responses are explicit.


*Drew Rice, 2016.*
