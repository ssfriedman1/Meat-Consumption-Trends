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
While my final repository does not show it, I first begain my data cleaning by coding a manual way to add continent values to each of the data points in the dataset. This was an extremely time and code entensive task until I was able to understand and impliment the .mask function, which cut down my program to no more than 7 lines for the 7 continents. 
![Mask Func](mask.png?raw=true "Mask Function")

