# DSCI100_project
UBC DSCI100 Group Project

# Project Proposal (DUE DATE UPDATED MARCH 5)
List of datasets
1. COVID-19 https://github.com/owid/covid-19-data/tree/master/public/data
   - Updated daily
   - The variables are confirmed cases, deaths, hospitalizations, and testing, as well as other variables of potential interest
   - missing data in some variables
  
2. Video Game Sale https://www.kaggle.com/gregorut/videogamesales
   - sale data from 2009 to 2016, scraped from vgchartz.com. Cleaned.
   - contains variables: rank, name, platform, year, genre, publisher, sales (in NA, EU, JP, rest of the world).
   
   - Question: by introducing a new game to the market (eg. an adventure game), predict the global sales
   
   - things to investigate: 
   1. the customers' preference shifts in different genres over years (maybe top 3)
   2. platform sales
   3. game publisher's sales percentage (maybe top 5) in total sales

   - predict that the sales for all games are reduced over the years because of increasing options available on the market
   
   
3. COVID-19 Lung Images https://www.kaggle.com/c/dlai3/data
   - contains train and test sets

To do list:
- [x] email Eric(TA) to confirm the usability of the above datasets
- [ ] formulate predictive questions from each datasets
- [ ] vote and finalize the project
- [x] set up the next ZOOM meeting - Thursday March 3rd. 8 pm https://ubc.zoom.us/j/61731167482?pwd=dWxIekFhUnJEcVJRb2lZOXUyWWlIQT09

Specific expectations for the proposal:
Each group is expected to prepare a 1 page (max 500 words) written proposal that identifies the dataset they plan to work on, as well as the question they would like to answer using that dataset for their group project. The proposal should be done in a Jupyter notebook, and then submitted both as an .html file (File -> Download As -> HTML) and an .ipynb file that is reproducible (i.e. works and runs without any additional files.)

Each proposal should include the following sections:

1. Title
2. Introduction:
Provide some relevant background information on the topic so that someone unfamiliar with it will be prepared to understand the rest of your proposal
Clearly state the question you will try to answer with your project
Identify and describe the dataset that will be used to answer the question

Preliminary exploratory data analysis:
[x]Demonstrate that the dataset can be read from the web into R
[x]Clean and wrangle your data into a tidy format 

[ ]Using only training data  --> need to split the dataset into 2
summarize the data in at least one table (this is exploratory data analysis).
An example of a useful table could be one that reports the number of observations in each class, the means of the predictor variables you plan to use in your analysis and how many rows have missing data. 
Using only training data, visualize the data with at least one plot relevant to the analysis you plan to do (this is exploratory data analysis). An example of a useful visualization could be one that compares the distributions of each of the predictor variables you plan to use in your analysis.

3. Methods:
Explain how you will conduct either your data analysis and which variables/columns you will use. Note - you do not need to use all variables/columns that exist in the raw data set. In fact, that's often not a good idea. For each variable think: is this a useful variable for prediction?
Describe at least one way that you will visualize the results


4. Expected outcomes and significance:
What do you expect to find?
What impact could such findings have?
What future questions could this lead to?
