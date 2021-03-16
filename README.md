# Binary Classification from Scratch

Data Analysis, Data Cleaning and Classifcation on four popular UCI datasets using Logistic Regression and Naive Bayes, built from scratch without using machine learning libraries. The project was split into 3 tasks: (1) Aquire, preprocess and analyze the data, (2) Implement/Build the machine learning models, and (3) Run the models and additonal experiments.

Datasets used: Adult Census, Breast Cancer Diagnosis, Ionoshere Data, and White Wine Quality from the UCI dataset archive

writeup.pdf: The main report of the project

## Task 1: Acquire, Preprocess and Analyze the Data
Acquire the data from UCI datasets, clean the data, and perform basic statistics to better understand the Data. This included but not limited to removing NaN values, modifying features if necessary, looking at probability distributions and correlations of features, and splitting the data into testing and training sets.

## Task 2: Implement/Build the Machine Learning Models
Implement/Build both Models from Scratch. 

Logistic regression with full batch gradient descent for optimization

Naive Bayes with the appropriate type of liklihood for the features of the datasets

## Task 3: Run Models and Experiments
Used 5 fold cross validation to estimate accuracy in all of the experiments.

Experiments Included:
1. Compare the accuracy of Naive Bayes and Logistic Regression on the four datasets
2. Test different leanring rates for gradient descent applied to logisitc regression
3. Compare the accuracy of the models as a function of the size of the dataset (controlling the training size)

## Jupyter Notebook Files
1. binary_adult_census.ipynb: Loads, cleans, analyzes and implements models on the Adult Census Dataset
2. binary_breast_cancer_diagnosis.ipynb: Loads, cleans, analyzes and implements models on the Breast Cancer Diagnosis Dataset
3. binary_ionosphere.ipynb: Loads, cleans, analyzes and implements models on the Ionosphere Dataset
4. binary_white_wine_quality.ipynb: Loads, cleans, analyzes and implements models on White Wine Quality Dataset

<object data="writeup.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="writeup.pdf">
        <p>Please read writeup.pdf for full results and discussion. You can download the PDF to view it: <a href="writeup.pdf">Download PDF</a>.</p>
    </embed>
</object>
