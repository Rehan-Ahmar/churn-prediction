# Predicting Customer Churn using Apache Spark

## Table of Contents

1. [Project Motivation](#motivation)
2. [Installation](#installation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Acknowledgements](#acknowledgements)


<a name="motivation"></a>
## Project Motivation

This project was created as part of Udacity's Data Scientist for Enterprise nanodegree. Here I have analyzed the log file of a music streaming service 'Sparkify' and built a machine learning model for predicting customer churn using Apache Spark. The full dataset is quite large (12GB).


<a name="installation"></a>
## Installation

The final code was run on IBM Watson Studio using Default Spark Python 3.5 XS runtime.

Libraries Used : numpy, pandas, matplotlib, seaborn, pyspark


<a name="files"></a>
## File Descriptions

  - **Sparkify.ipynb** : Contains detailed analysis, visualizations and modeling for  a subset of data.
  - **sparkify_app_ibm.ipynb** : Contains the final code run on IBM Watson Studio.


<a name="results"></a>
## Results

The final Random Forest Classifier model gives an F1-score of 0.88, which is quite satisfactory. There is still a lot of scope for improvements, like creating new features from the data and trying out other models and hyperparameters.


<a name="acknowledgements"></a>
## Acknowledgements

Thanks to Udacity for the data and course material.
