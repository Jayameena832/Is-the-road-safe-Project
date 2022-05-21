# Is-the-road-safe-assignment
ML program for the assignment of the project "Is the road safe?" by the programming club, IIT Kanpur 

B) From where you obtained the dataset?( Mention the source and provide the link)

The dataset is taken from the website UCI Machine Learning Repository. The name of the dataset is Combined Cycle Power Plant. 
This is the link of the website- https://archive.ics.uci.edu/ml/datasets/combined+cycle+power+plant
This is the link for the dataset - https://archive.ics.uci.edu/ml/machine-learning-databases/00294/CCPP.zip (Sheet 1 of the Excel sheet in the Zip file)

C) Within 80 words summarize why you chose the particular algorithm in question A.  

**On testing the given regression with other regression types we found that its evaluation score was highest among all(We can check this by using following code snippet for every regression model and comparing there evaluating score:
from sklearn.metrics import r2_score
r2_score(y_test, y_pred))
Hence random forest regression is used for the non-linear dataset chosen above.**

Also Random forest Regression has the following benefits:-
-Random forest algorithm can be used for both classifications and regression task.
-It provides higher accuracy through cross validation.
-Random forest classifier will handle the missing values and maintain the accuracy of a large proportion of data.
-If there are more trees, it won’t allow over-fitting trees in the model.
-It has the power to handle a large data set with higher dimensionality.

Submitted By-
Jaya Meena
200472
BT Y20 CSE
