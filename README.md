## Meat Consumption Trends Statistical Analysis and Data Visualization

The goal of this project was to analyze the consumption of meat throughout the world with respect to different metrics - GDP, Livestock count, Population - with the goal to better understand which countries consume more meat and why. 

## WHY?
As someone who recently started consuming a more plant based diet, I wanted to begin to understand what the meat consumption trends looked like world wide. I started with the assumption and knowledge that consumption of meat - especially red meat - was often a status symbol, and those with more money consumed more meat in general. As you will later see, my assumptions were spot on, and the relationship between GDP and meat consumption were linearly related. 

## HOW ?
To complete this project, I worked on my skills using some of the most important data science packages in Python - Tableau, Matplotlib, Pandas, and Seaborn. 

<img src= "https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" alt = "Python Logo" width= "100" height="100" /> <img src= "https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original.svg" alt = "Pandas Logo" width= "100" height="100" /> <img src= "https://matplotlib.org/_static/logo2_compressed.svg" alt = "Matplotlib Logo" width= "100" height="100" /> <img src= "https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original-wordmark.svg" alt = "Numpy Logo" width= "100" height="100" /> <img src="https://github.com/mwaskom/seaborn/blob/v0.12.0b2/doc/_static/logo-wide-lightbg.svg" alt = "Seaborn Logo" width = "100" height = "100" />

## WHAT ?

### Data Collection ###
I first had to find many datasets involving meat and animal product consumption, which I found on: https://ourworldindata.org. I downloaded the datasets in the form of .csv files and opened them using my code editor of choice - VSCode. I then began the process of cleaning and analysing the data. 

### Data Cleaning ###
While my final repository does not show it, I first begain my data cleaning by manually coding a method to add continent values to each of the data points in the dataset. This was an extremely time and code entensive task and was made completely useless when I learned to understand and impliment the .mask function, which cut down my program to no more than 7 lines for the 7 continents. 
![Mask Func](/images/mask.png?raw=true "Mask Function")

### Dataframe Merging
After I had cleaned the data, my next step was to merge the many dataframes together, so that I could reference the same data for all my analysis as well as compare data from the different dataframes with more ease. I did this by using the pandas merge function in combination with lambda to be able to merge all the dataframes simultaniously using an outer merge, meaning that all data from all the dataframes was included without any repeats. I then renamed the column titles so that I could address them more easily later on. 

![Merge Func](/images/merging.png?raw=true "Mask Function")

## GDP Analysis ##
### First Visual ###
For my first analysis, I wanted to explore the connection between GDP per capita and meat comsumption quantity. I started out by graphing the two values on the x and y axis respectively. The graph that was formed showed a clear correlation between GDP and meat consumption, as the data followed a clear trend. I noticed however that the data was very cluttered, and it was hard to distinguish individual data points. That I would tackle in the next steps.

![First Graph](/images/first_graph.png?raw=true "First graph")

### Second Visual ###
To better visualize the data, I first decided to only view one year, 2017 which was the data with the least missing values in terms of meat food supply quantity. This meant that that there was now only one data point per country. Additionally, I used a log scale on the x-axis to stretch out the data points closer to the origin and allow for more normal distribution of the data along the x-axis. 
![Sec Graph](/images/second_graph.png?raw=true "Second Graph")



![Last Graph](/images/final_graph.png?raw=true "Final graph")
