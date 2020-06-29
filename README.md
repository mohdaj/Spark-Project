
# Spark Project-Capstone Project

## Table of Contents

1. [Project Motivation](#motivation)
2. [Dependencies](#dependencies)
3. [Files Description](#description)
4. [Results](#results)
5. [Acknowledgements](#acknowledgements)
6. [Credit](#credit)



### Project Motivation <a name = "motivation"></a>

This project is the capstone project in the Data Scientist Nanodegree, the aim of this project is to create a prediction model that will be able to help identify users that will cancel their Sparkify subscription. Sparkify is a music streaming service semilar to Spotify and Pandora , this dataset contains two months of sparkify user behavior log. The log contains basic information about the user and information about a single action. A user can contain many entries. In the data, a part of the user is churned, through the cancellation of the account behavior can be distinguished.

### Dependencies <a name = "dependencies"></a>

All the following libraries are needed to implement this project:

**Python**<br>
**Pandas**<br>
**Matplotlib**<br>
**Seaborn**<br>
**PySpark**<br>
**Spark**<br>

### Files Description <a name = "description"></a>

1 - **Sparkify.ipynb**: The main file that contain the code.

2 - **mini_sparkify_event_data.json**: The data used in this project.

### Results <a name = "results"></a>

We trained model Random Forest on the dataset. The metric we used to evaluate performance is F-1 Score as that gives us a better representation of the model performance. The modeling succeeded in predicting churn After finding the F1-Score for the model, I found that Random Forest Classifier was the best for predicting churn.

The final metrics for our Random Forest Classifier are as follows: <br>
The F-1 Score is 0.6894247833803111<br>

My blog post on Medium website is [Here](https://medium.com/@engmoh24/predict-user-churn-using-pyspark-c8b2b66e4172)

### Acknowledgements <a name = "acknowledgements"></a>

Udacity has to be acknowledged for giving me this wonderful project.

### Credit<a name = "credit"></a>

Credit goes to Sparkify for providing the data used in this project.