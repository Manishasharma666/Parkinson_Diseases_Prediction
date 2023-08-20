# Parkinson's Disease Prediction

## What is parkinson disease?

Parkinson’s disease is a brain disorder that causes unintended or uncontrollable movements, such as shaking, stiffness, and difficulty with balance and coordination.
Symptoms usually begin gradually and worsen over time. As the disease progresses, people may have difficulty walking and talking.
It's estimated that 10 million people worldwide suffer from this disease.
Parkinson’s illness is generally incurable, however medication can frequently help control the symptoms.

## Objective of doing this project
Currently non specialist clinics have not been able to definitively diagnose the disease, especially in early stages of symptoms.
Some common methods for identifying parkinson’s disease are: PET scan, MRI scan, CT scan.Parkinson can not be diagnosed efficiently using traditional methods.
So, we can use machine learning algorithms that uses statistical measures to identify parkinson disease.

## Dataset Information

The dataset includes various biological voice measurements taken from 31 individuals, 23 of whom have parkinson’s disease.
There are 195 voice recordings of these people and column represents specific voice measurement.
It has a status column with value 0 for healthy person and 1 for parkinson disease.
Each patient has about 6 recordings in dataset which is in csv format.

## Procedure

1.Import useful libraries in colab notebook.
2.Read  a csv file of dataset.
3.Preprocess dataset i.e clean dataset and remove null values if any.
4.Visualize different features using matplotlib and seaborn.
5.Dividing dataset into train and test 
6.Use a model and train it using training dataset.
7.Use the test data to test the model.
8.Calculate accuracy of each model.
9.Building predictive system.

## Models used

1. logistic regression
2. decision tree
3. random forest
4. naive bayes classifier
5. knn
6. svm

## Result
  SVM and Decision tree gives the maximum accuracy i.e 92 %.

## Conclusion
Parkinson’s disease is the second most dangerous neurodegenerative disease which has no cure till now and to make it reduce prediction is important. 
In this project, we have used six various prediction models to predict the Parkinson’s disease which are Machine Learning Techniques i.e.
KNN, Naïve Bayes , Logistic Regression , decision tree, random forest, SVM. 
The dataset is trained using these models and we also compared these different models built using different methods and identified the best model that fits.
The aim is to use evaluation metrics such as Accuracy, confusion matrix that produce the predicted disease efficiently.

## Future Scope

In future, these models can be trained with different datasets that have the best features and can be
predicted more accurately. If the accuracy rate increases, it can be used by the laboratories and
hospitals so that it is easy to predict in early stages.
These models can be also used with different medical and disease datasets. In future the work can be extended by building a hybrid model that can find more than one disease with an accurate dataset and that dataset has common features of
two diseases. 
In future the work can be extended to build a model that may extract more important
features among all features in the dataset so that it produces more accuracy.

## Screenshot of User Interface made with streamlit library of python








