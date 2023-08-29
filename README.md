# Udacity - Data Scientist Nanodegree Program

For more information take a look at the corresponding [blog post](https://medium.com/@grinsecat/predicting-user-churn-of-a-fictional-music-plattform-with-pyspark-ffc7fa98f31b)
## Project - Sparkify

- [Installations](#inst)
- [Project Motivation](#promot)
- [File Description](#filedesc)
- [Instructions](#instruct)
- [Licensing, Authors and Acknowledgements](#license)

<a id='inst'></a>
## Installations
Anaconda Jupyter Notebook with Python3
Pyspark v3.4.1

### Packages
- pyspark.sql
- pyspark.ml
- re 
- pandas
- seaborn
- matplotlib
- datetime

### Data
This workspace uses the tiny subset (128MB) of the full dataset available (12GB).

<a id='promot'></a>
## Project Motivation
The main focus of this Project is to learn learn how to manipulate large and realistic datasets with Spark to engineer relevant features for predicting churn.
We will use the Spark MLlib to build machine learning models with large datasets, far beyond what could be done with non-distributed technologies like scikit-learn.

Predicting churn rates is a challenging and common problem that data scientists and analysts regularly encounter in any customer-facing business. Additionally, the ability to efficiently manipulate large datasets with Spark is one of the highest-demand skills in the field of data.
<a id='filedesc'></a>
## Files
> Sparkify.ipynb - Jupyter Notebook where all the code is running

> README.md

<a id='instruct'></a>
## Notebook - Structur
- Project Informations
- Load and Clean Dataset
- Exploratory Data Analysis
- Feature Engineering
- Modeling
- Conclusion

## Summary

The for tested models produced following results:

|model classifier|accuracy|f1_score|
|----------------|--------|--------|
|logistic regression|0.680851|­0.551576|
|gradient boost tree|0.638298|0.583087|
|naive bayes        |0.680851|0.551576|
|random forest      |0.723404|0.640996|


- all evaluation values are relatively low
- random forest classifier has the best prediction scores in accuracy and f1
- logistic regression and naive bayes classifier show the exact same values in accuracy and f1
- gradient boost tree classifier has the lowest accuracy but the second highest f1 score


<a id='license'></a>
## Licensing, Authors and Acknowledgements

Thanks to Udacity for providing the project and the environment!

