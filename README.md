# Binary Classification from Scratch

Data Analysis, Data Cleaning and Classifcation on four popular UCI datasets using Logistic Regression and Naive Bayes

writeup.pdf: The main report of the project

## Task 1: Acquire, Preprocess and Analyze the Data
Acquire the data from UCI datasets, clean the data, and perform basic statistics to better understand the Data

Datasets used: Adult Census, Breast Cancer Diagnosis, Ionoshere Data, White Wine Quality

### Jupyter Notebook Files
1. DatasetAnalysis_AdultCensus.ipynb: Loading, preprocessing and analysis of the Adult Census Dataset
2. DatasetAnalysis_BreastCancerDiagnosis.ipynb: Loading, preprocessing and analysis of the Breast Cancer Diagnosis Dataset
3. DatasetAnalysis_Ionosphere.ipynb: Loading, preprocessing and analysis of the Ionosphere Dataset
4. DatasetAnalysis_WhiteWineQuality.ipynb: Loading, preprocessing and analysis of the White Wine Quality Dataset

## Task 2: Implement the Models
Implement Both Models from Scratch. 

Logistic regression with full batch gradient descent for optimization

Naive Bayes with appropriate type of liklihood for features of the datasets

### Jupyter Notebook Files (Combined with Task 3)

## Task 3: Run Experiments
Used 5 fold cross validation to estimate accuracy in all of the experiments.

Experiments Included:
1. Compare the accuracy of Naive Bayes and Logistic Regression on the four datasets
2. Test different leanring rates for gradient descent applied to logisitc regression
3. Compare the accuracy of the models as a function of the size of the dataset (controlling the training size)

### Jupyter Notebook Files
1. AdultCensus_Task2_Task3.ipynb: Loads, cleans, and implements models on Adult Census Dataset
2. BreastCancerDiagnosis - Task2_Task3.ipynb: Loads, cleans, and implements models on Breast Cancer Diagnosis Dataset
3. Ionosphere_Data - Task2_Task3.ipynb: Loads, cleans, and implements models on Ionosphere Dataset
4. WhiteWineQuality - Task2_Task3.ipynb: Loads, cleans, and implements models on White WIne Quality Dataset

Read writeup.pdf for full results and discussion

<object data="writeup.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="writeup.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="writeup.pdf">Download PDF</a>.</p>
    </embed>
</object>

<embed src="writeup.pdf" type="application/pdf" width="100%" height="600px" />