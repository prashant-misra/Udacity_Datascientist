# Seattle AirBNB Data Analysis
# Motivation for this data science project:
The current Seattle Airbnb project is done as a part of Udacity Data Scientist Nanodegree.  The datasets for this project are collected form Kaggle repository. There are three data sets called reviews, listings and calendar and the data collected from 2016.  The aim of this project is to analyse the data sets and find out the answers for the following questions:
This project is executed by the CRISP-DM mentioned in the Udacity tutorials. The following are the steps involved:
1)Business Understanding
 2)Data Understanding 
3)Data Preparation 
4)Modeling
5)Evaluation
6)Deployment

# Installations required:
The code was written in Python 3.6(Preferred version). Additional installations are not required for the project
# Technologies used:
1)	Python
2)	Libraries of Python: numpy ,pandas ,sklearn, nltk, matplotlib, seaborn
3)	Jyupiter Notebook

# Questions analyzed:
1)Achieving the best possible price for a given accommodation.
2)Does the location has any effect on price
3) Predicting the price using Machine Learning algorithms:

# Answers Found:
1) From the Accommodates Vs Price graphs and the correlation Heatmap, we can say that how many people the listing can accommodate is the main factor for price for that particular listing. Number of beds, bedrooms and bathrooms and guests included are also highly correlated. These are features of accommodation. These are the other features that can be considered.
2) We can observe that Downtown, Magnolia, Queen Anne, Cascade, West Seattle
3) In this module, we have used two algorithms namely Random forest and Support vector Machines to predict the price of an Airbnb We observed that the R2 value of SVM(30%) is less than R2 value of Random Forest(54%). Thus, we can conclude that is a better performing model. We can understand that Random Forest can explain atleast 54% pf price variance.
# Acknowledgements:
Reference for the Heatmap: https://stackoverflow.com/questions/12286607/making-heatmap-from-pandas-dataframe

# Medium Post can be found  [here](https://medium.com/@penumartisatish9/seattle-airbnb-data-analysis-udacity-data-scientist-nano-degree-487e1a925ae1/)
