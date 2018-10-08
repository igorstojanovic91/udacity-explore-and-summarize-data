# udacity-explore-and-summarize-data

# Udacity Data Analyst Term 2 Project 2: Explore and Summarize Data

In this project, R was used to apply exploratory data analysis techniques to explore relationships in one variable to multiple variables and to explore a selected data set for distributions, outliers, and anomalies.

Project description from Udacity:
Exploratory Data Analysis (EDA) is the numerical and graphical examination of data characteristics and relationships before formal, rigorous statistical analyses are applied.

EDA can lead to insights, which may uncover to other questions, and eventually predictive models. It also is an important “line of defense” against bad data and is an opportunity to notice that your assumptions or intuitions about a data set are violated.

The project takes two datasets as input (red and white wine) and creates a combined data set. Within the project I applied a Univariate Plots Section, a Bivariate Plots Section and a Multivariate Plots Section.


# How to run the script
In order to see the project, you will need to install R. You can download and install R from the Comprehensive R Archive Network (CRAN). After installing R, you will need to download and install R Studio. 

Finally, you will need to install a few packages. Open R Studio and install the following packages using the command line:

install.packages("ggplot2", dependencies = T) 
install.packages("knitr", dependencies = T)
install.packages("dplyr", dependencies = T)

# Dataset
The combined dataset of red and white wine contains 6497 observations and 13 variables:

1 - fixed acidity (tartaric acid - g / dm^3)
2 - volatile acidity (acetic acid - g / dm^3)
3 - citric acid (g / dm^3)
4 - residual sugar (g / dm^3)
5 - chlorides (sodium chloride - g / dm^3
6 - free sulfur dioxide (mg / dm^3)
7 - total sulfur dioxide (mg / dm^3)
8 - density (g / cm^3)
9 - pH
10 - sulphates (potassium sulphate - g / dm3)
11 - alcohol (% by volume) 
Output variable (based on sensory data): 12 - quality (score between 0 and 10)
13- type (red or white)


# Files
- Project EDA Igor Stojanovic.rmd
- Project_EDA_Igor_Stojanovic.html
- wineQualityReds.csv
- wineQualityWhites.csv

# Reflection
The EDA task was a very interesting project for the author trying to get insights into the chemical substances of wine and its influence on quality. Although the author was very exited in the beginning of the project, he had to deal with some obstacles and disappointments. It was nice to gain an understanding of the single variables of the data set, but as soon as the varaiables were plotted against each other, it was rather disappointing to see lower levels of correlations, especially regarding quality. The author at that point assumed that it is not gonna be easy to try to create a good predictive model for the quality of wine. Nevertheless, it was an interesting overall project for the author to apply his new skills on a data set with only little guidance of the template. On the other hand, this point makes it hard to decide when you reach your ending point of the analysis, as the analysis could go forever. The author found it helpful to have clear goals to understand primarily the influence on quality, rather the influence on chemical substances among each other.

This aspect could certainly offer possibilities for future research, on the other hand the analysis show that we need other data or metrics to understand how quality of wine is perceived from an individual to build better models. It would be maybe interesting to add as well the kind of grapes or the level of wine expereience of the individual testers.

Overall, the project was a great expereince.



