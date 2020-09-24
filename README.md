# Chrissy Cho's Supervised Machine Learning
### Table of Contents
[ 1. Project Overview ](#desc)<br /> 
[ 2. Resources ](#resc)<br /> 
[ 3. Objectives ](#obj)<br /> 
[ 4. Challenge Overview ](#chal)<br /> 
[ 5. Challenge Objective ](#chalsum)<br /> 
[ 6. Final Thoughts ](#find)<br />


<a name="desc"></a>
## Project Overview
In this module, we've built and evaluated several machine learning models to predict credit risk. 

<a name="resc"></a>
## Resources
- Data Source: [challenge_data](https://github.com/chrissycho/Supervised_Machine_Learning/blob/master/Module-17-Challenge-Resources/LoanStats_2019Q1.csv)
- Software: Jupyter Notebook, Python3
- Libraries: pandas, numpy, pathlib, collections, sklearn, imblearn

<a name="obj"></a>
## Objectives
- Explain how a machine learning algorithm is used in data analytics.
- Create training and test groups from a given data set.
- Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
- Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
- Compare the advantages and disadvantages of each supervised learning algorithm.
- Determine which supervised learning algorithm is best used for a given data set or scenario.
- Use ensemble and resampling techniques to improve model performance.
<a name="chal"></a>
## Challenge Overview
In this challenge, we've built and evaluated several machine learning models to assess credit risk, using data from LendingClub; a peer-to-peer lending services company. The credit risk data was an inherently unblaanced classification problem. 

<a name="chalsum"></a>
## Challenge Objective
- Implement machine learning models.
- Use resampling to attempt to address class imbalance.
- Evaluate the performance of machine learning models.


<a name="find"></a>
## Final Thoughts
Upon inspecting the data at first, we went through a few preprocessing of the data such as removing any null values and transforming data with object type to numeric values. Then, we split the data into training and testing to fit the traditional machine learning. We first started off with naive random oversamling to pick random samples from the minority group to oversample. We've written the analysis of each model in the Juyter Notebook along with the codes. We then resampled the data with SMOTE oversampling, undersampling using Cluster Centroids, and the SMOTEENN combination sampling in order. Based on the needs of business, one should define which performance score will be used (precision, recall, or F1). For this assignment, we've picked recall as our performance score since we want to know how many high risk loans are correctly identified. 