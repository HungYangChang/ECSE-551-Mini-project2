# Naive Bayes Classifier - Reddit Comments classification
### Contributors: Jonathan Arsenault, Hung-Yang Chang, Anan Lu
### Mini-Project 2 - ECSE 551 McGill University

## Abstract
Text classification is a well-known machine learning problem. In this project, a classifier is built that identifies the subreddit from which a comment originated. Two separate algorithms are used, a multinomial Naive Bayes classifier and a support-vector machine classifier. To obtain optimal performance from these classifiers, the raw text comments must be converted to features. The majority of this report presents the methods used to construct the features which yielded the best results. Through 5-fold cross-validation, the best results were found using the multinomial Naive Bayes classifier with a tuned Laplace smoothing parameter, and assuming a uniform distribution of each class. Results were further improved by selecting features which were determined to be the most relevant using a chi-squared statistical test. This classifier was then applied to a test set, yielding a preliminary accuracy of 93.1% according to Kaggle. 

## Code.zip
The code.zip contains 5 files:
* 2 Colab notebook files - miniproject_2_final.ipynb and miniproject_2_supplemental.ipynb
  * miniproject_2_final.ipynb contains all utility functions for our own Naive Bayes classifier, and all experiments to improve model performance. One other sklearn classifier, SVM is utilized here to compare with our own classifier.
  * miniproject_2_supplemental.ipynb contains each step for choosing parameters and preprocessing methods for Multinomial Naive Bayes model. The result is shown as Table in section 4.1.1  Multinomial Naïve Bayes in Report.pdf
* 3 Dataset files - train.csv, test.csv, and Submit.csv
  * Submit.csv is the prediction of our own Naive Bayes function with an accuracy of 93.1% according to Kaggle.
* 1 ReadMe file - ReadMe.md

## Report.pdf
All experiments are summarized in Report.pdf

## Code Usage - (Python 3.6, Colab)
1. Please Upload to python notebook (.ipynb file) to Colab
2. Select the required notebook and select "Run" in each code.
3. Note: Some of the codes are involved gird searching and may not be able to run in colab due to memory limit.

## More info
Code are also available on GitHub link (https://github.com/HungYangChang/ECSE-551-Mini-project2)
