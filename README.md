# Using images of breast masses to predict the prognosis of breast cancer (into two classes: non-recurrent (N) and recurrent (R)) and evaluating the model

Data downloaded from the UCI machine learning data repository https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wpbc.data

(The characteristics of the images have been recorded and turned into strucured numerical data)

A random forest model was built to predict the prognosis.

The accuracy of the model was assessed.
Assuming N (non-recurrent) is positive and R (recurrent) is negative, the overall accuracy is 0.717, the precision is 0.75, recall is 0.93, specificity is 0.12, sensitivity and recall are both 0.93.
The numbers above indicate that the model is decent at predicting positive data (N) but bad at predicting negative data (R). This may be partially due to unbalanced class distribution (N greatly outnumbering R).

An ROC curve was built.

