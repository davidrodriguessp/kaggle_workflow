*Author: David Rodrigues* | https://www.linkedin.com/in/davidrodrigues/ | davidrodriguessp@hotmail.com | https://github.com/davidrodriguessp

# Building a Workflow to Compete in Kaggle: Predicting which Passengers Survived the Titanic Shipwreck

![titanic](https://images.unsplash.com/photo-1500077423678-25eead48513a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80)

<center>Photo by Руслан Гамзалиев on Unsplash</center>

The objective of this project is to provide a guide on how to build a project to take part in Kaggle competitions. [Kaggle](https://www.kaggle.com/)  is a website in which companies propose a challenge in which machine leaning practitioners compete and try to provide the best algorithm to predict a phenomenon. The one that manages to reach the best accuracy wins the competition and receives an award.

For this project we used the famous [Titanic](https://www.kaggle.com/c/titanic) competition, in which a dataset with passanger characteristics is provided and participants need to build a model to try to predict passangers survival. Two datasets are available in the website: the training set (`train.csv`) and test set (`test.csv`). [Here](https://www.kaggle.com/c/titanic/data) you will find the datasets and a data dictionary describing each of the columns.

The workflow follows the 7 steps below:
1. **Objective**: define the *question to be answered* and the objective of the project.
2. **Data cleaning**: remove irrelevant columns, deal with missing values, deal with non-numerical data, check for class imbalance.
3. **Data exploration and Feature Engeneering**: find patterns and relations between columns and do feature engeneering, that is, create new features out of the ones available in the raw data.
4. **Feature selection**: select the best subset of features, check for collinearity and relationship with the target column.
5. **Model selection/tuning**: training a number of models with different hyperparameters to find the best performer.
6. **Final Model**: train the final model with all training data available and make predictions.
7. **Submission**: create a file to submite to Kaggle.

You can find three files on this repository:
Train dataset: train.csv
Test dataset: test.csv
Final notebook with the full report: Kaggle Workflow.ipynb
