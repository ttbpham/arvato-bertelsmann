# Bertelsmann/Arvato Project

This is final project of the Udacity Data Scientist Nanodegree. The goal of the project is to use appropriate data analytics tools and methodologies to predict potential customers for Arvato’s mail order organic products.
Historical data on general population demographics, on customers and on client response to previous campaign have been provided to assist in predicting which ones from general population are likely to be good responders to Arvato’s marketing campaign.  
There are 3 major sections in this project:
1.	Understanding business problem and data characteristics
2.	Using Unsupervised Machine Learning to identify what segments of general population that match Arvato’s existing customer segments
3.	Using Supervised Machine Learning to predict which customers are likely to response to company’s marketing campaign.


## Table of Contents

* [File Descriptions](#file-description)
* [Instructions](#instructions)
* [Creator](#creators)
* [Acknowlegement](#acknowlegement)

## File Descriptions

4 datasets provided by Arvato will be explored in this project:
1.	Udacity_AZDIAS_052018.csv: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
2.	Udacity_CUSTOMERS_052018.csv: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
3.	Udacity_MAILOUT_052018_TRAIN.csv: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
4.	Udacity_MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

And 2 metadata files associated with these datasets:
1.	DIAS Information Levels - Attributes 2017.xlsx is a top-level list of attributes and descriptions, organized by informational category.
2.	DIAS Attributes - Values 2017.xlsx is a detailed mapping of data values for each feature in alphabetical order

Terms and Conditions file - terms.pdf: detailed conditions of downloading and using datasets provided by AZ Direct GmbH for the Bertelsmann/Arvato Capstone projects

arvato_project_workbook.ipynb: contains all the codes for this project

Arvato-Bertelsmann.pdf: project report contains detailed data analysis and algorithms used in clustering and predicting Arvato's potential customers.


## Instructions

The codes are written in Python 3, the following Python libraries are required for successful execution of arvato_project_workbook.ipynb

* numpy
* pandas
* matplotlib
* seaborn
* math
* operator
* sklearn


Refer to [Python Packaging User Guide](https://packaging.python.org) for checking and installing missing libraries on your system.


## Creators

Thuy Pham  - [https://github.com/ttbpham](https://github.com/ttbpham)

## Acknowlegement

This project is under the Udacity Data Science Nanodegree.
