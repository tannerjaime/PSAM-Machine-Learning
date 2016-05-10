###Machine Learning Assignment 1: Classification


####Data 
Amazon Fine Food Reviews The Amazon Fine Food Reviews dataset consists of 455,000 food reviews Amazon users left up to October 2012. 

####Classification Taske
Train a model to best predict helpful, a boolean indicator that a review was deemed helpful by other shoppers. This was defined as:
(data.HelpfulnessDenominator > 3) & (data.helpScore >= 0.9)  

--------------
####Final Model Decision
In my final model for this assignment, I am using the Perceptron in order to classify true postives, as well as Naive Bayes in order to determine true negatives. 


####Performance Over Time
Model found in upper left corner. Organized by date. 

######3/01/2016
Features relating to punctuation and counts in the text and usernames

![](Plots/Assgnmnt1Results3:01.png)


######3/29/2016
Changed from hashing vectorizor to TD-IDF

![](Plots/Assignment1Results3:29.png)


######4/21/2016
Added some features related to the review Summary 

![](Plots/Assignment1Results4:21.png)


######4/22/2016
Added features related to capital letter counts in both the Summary and the Text

![](Plots/assignemnt1Results4:22.png)


