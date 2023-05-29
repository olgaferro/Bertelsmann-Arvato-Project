# === [Bertelmann/Arvato  Project] ===


# === INSTALLATION ===
The code contained in this repository was written in Python 3, and requires the following Python packages: 

seaborn
numpy 
pandas as pd
matplotlib.pyplot 
sklearn.preprocessing
xgboost

to install:

pip install "package-name"



# === DESCRIPTION ===

In this project we are going to  individuals whose can probabilities to become a new customers to  Bertelsmann Arvato Analytics. 


The goal of this project is to analyze demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information for the general population. To approach this  is going to use  unsupervised learning techniques to perform customer segmentation, identifying the parts of the population that best describe the core customer base of the company. 


# === FILES PROVIDED FOR Bertelmann ARVATO ===

-- Files associated Demographics data  for--



AZDIAS:          the general population of Germany; 
CUSTOMERS:        customers of a mail-order company; 

-- Files associated Demographics data for individuals who were targets of a marketing campaign

MAILOUT_TRAIN

MAILOUT_TEST 

--  Attributes files

./DIAS Information Levels - Attributes 2017.xlsx) is a top-level list of attributes and descriptions, organized by informational category.

./DIAS Attributes - Values 2017.xlsx:is a detailed mapping of data values for each feature in alphabetical order.



## 1. PROJECT MOTIVATION

With these file information about population in Germany the goal is use a model to predict which individuals are most likely to become a future customers for the company.




# === FILE STRUCTURE ===


- Arvato Project Workbook.ipynb
- DIAS Attributes - Values 2017.xlsx
- DIAS Information Levels - Attributes 2017.xlsx
- README.md




# RESULTS


I trained the differents classifiers with the next results, before scaling:

	classifier					roc_score	train_time
    
3	XGBClassifier               0.76009	    5.05429

1	GradientBoostingClassifier  0.740655    26.44362

0	AdaBoost                    0.712455    5.030592

2	Random Forest               0.60152     4.287085

5	Decision Tree               0.511529    1.126603

4	Nearest Neighbors           0.49322     0.64965

From the table above we can conclude that the betters scores are given by XGBoost, AdaBoost and Gradient Boosting classifiers. 
Adaboost and Gradient are close by  Ada is so fast than the Gradient.   

# BLOG

https://datasciencecourse2.wordpress.com/2023/05/16/bertelsmann-arvato-project/

## LICENSING, AUTHORES,ACKNOWLEDGMENTS

Arvato Bertelmann for providing the data and Udacity for provide the resources to work in the project (https://www.udacity.com/)



https://hersanyagci.medium.com/feature-scaling-with-scikit-learn-for-data-science-8c4cbcf2daff
https://seaborn.pydata.org/generated/seaborn.color_palette.html
https://stackoverflow.com/questions/62953704/valueerror-the-number-of-fixedlocator-locations-5-usually-from-a-call-to-set
https://ipython.readthedocs.io/en/stable/interactive/reference.html#magic-command-system
https://jupyter.org/install




