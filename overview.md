2 Types of ML
1. Supervised 
2. Unsupervised.
======================================
Supervised - 
1. Regression
2. Classification

Let's say I want to create a model such that when I give an age, it should give a weight for following dataset.
Age,Weight
24,62
25,63
21,72

2 types, dependent and independent feature
Weight - Dependent, since it's dependent on independent value
Age - Independent

In supervised, there would be one dependent feature and N independent features.

Regression Problem Statement
When you have a continous variable, it's regression problem. 
Similar to scatter plot and then plot a line such that y=mx+c.
This way we can find the value of y axis from x axis.

Classification Problem Statement
No of hours, no of play hours, no of sleep hours, PAss/Fail
Pass/Fail - Dependent features
When you have fixed no of categories, it's classification problem. When you have 2 categories, binary classification. more than 2, multi class classification.
==========================================
Unsupervised - 
1. Clustering
2. Dimensionality REduction

Dataset
Salary,Age
There's not op variable. No dependent variable.

Clustering problem statement
Let's say customer segmentation. Based on data, will find out similar groups. 
Each cluster will specify some info. Let's say young and great salary, more age but middle class salary etc. This would help us group togetther so that we need to target certain products for rich ppl, some for other ppl etc.

Dim Reduction problem statement
What if we have 1000 features, want to convert to 100 features. 
For ex, LDA, PCA
==============================
