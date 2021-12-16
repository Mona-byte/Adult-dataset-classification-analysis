# Adult-dataset-classification-analysis
This project paper gives an overview of a classification analysis of the adult dataset which was done in Jupyter notebook. The adult dataset was generated during a census in United States. The dataset consists of both categorical and continuous data. The aim of the project is to predict if a person would make more than 50k annually or not.

During the analysis, we handled missing data and changed categorical features to integers. We also used correlation results to determine feature selection criteria. The classification algorithms we used are: Decision Tree, KNN, NB, SVM and Perceptron. As a result of imbalanced classification, we used performance metrics like Confusion Matrix, Precision, Recall, AUC score to determine the best model fit. We used the stratified 10-fold cross validation to evaluate the prediction models. The perceptron-based AUC score of 0.89 was accepted since it is greater than 0.5.

In the first section, we define the problem and describe the features of the dataset. In the second section, we give information on the exploratory data analysis done and the preprocessing steps. In the third section, we talk about the analysis of the data and its results.
REPLICATION.
Inorder to replicate or run this project, one has to download the UCI adult dataset, specify the persons working directory in the script and it should run perfectly. 
The dataset can be downloaded at: https://archive.ics.uci.edu/ml/datasets/Adult
