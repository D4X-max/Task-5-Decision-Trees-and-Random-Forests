# Task-5-Decision-Trees-and-Random-Forests

# STEP 1 - Train a Descision Tree Classifier and visualize the tree
 1.I imported all the necessary libraries like pandas, numpy, matplotlib, sklearn, and graphviz
 2.Loaded the dataset
 3.prepared target variable
 4.Split the data into train and test split
 5.trained the descision tree classifier
 6.visualized using graphviz

# STEP 2 - Analyzing the overfitting and control depth
 1.created two arrays for trained and test scores
 2.Control depths by running a loop from 1 to 10
 3.Calculated the scores for each depth
 4.plotted the results on a graph that shows the tree depth vs accuracy

# STEP 3 - Training random forest and comparing accuracy
 1.Created and fitted train test sets into RandomForest Classifier
 2.Compared the accuracy for both random and descision tree 

# STEP 4 - Interpret feature importances
 1.Sorted and printed the features 
 2.Cp and thalach have highest importance

# STEP 5 - Evaluating using cross validation 
 1.imported the cross_val_score library from sklearn's model selection package
 2.passed the values for both the trees in the corss_val_score function 
 3.Printed the final values of both the trees 
