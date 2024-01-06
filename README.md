# Cancer-diagnosis-using-Machine-learning-
Classification of a cancer into 9 classes

# Problem
* Cancer is a very dangerous genetic disease that is caused by changes to the genes that control the way our cells function grow and divide.
* Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). 
* Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature.
* We need to develop a Machine Learning model that, using this knowledge base as a baseline, automatically classifies genetic variations.

# Real world objectives and constraints
* No Low latency Requirement 
* Interpretability is important.
* Errors can be very costly.
* Probability of a data-point belonging to each class is needed.

# Data
* We have two data files: one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations. 
* Both these data files are have a common column called ID
* Data file’s information: 
  * training_variants (ID , Gene, Variations, Class) 
  * training_text (ID, Text)

# Performance metrics
* Multiclass logloss and Confusion matrix


# Feature importance (univariate analysis)
* Checking wheather each feature is important or not for predicting yi
* Firstly we will featurize Gene feature using the two featurization techniques
* We will use the appropriate featurization based on ML models we use. For this problem with categorical features, one hot encoding is very useful for logistic regression.


# Implementation
* Trained Naive Bayes , KNN (k nearest neighbours), Logistic regression, Linear SVM (Support Vector Machine)
* Reduced the misclassification rate to 38% using Logistic Regression.

For more detailed explaination, please take a look at `.ipynb` or `.pdf` file.












