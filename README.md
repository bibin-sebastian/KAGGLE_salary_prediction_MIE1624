# KAGGLE_salary_prediction_MIE1624
MIE1624_courseassignment. Kaggle salary prediction

Kaggle is currently hosting an open data scientist competition titled “2018 Kaggle ML & DS Survey Challenge.” The purpose of this challenge is to “tell a data story about a subset of the data science community represented in this survey, through a combination of both narrative text and data exploration.” Kaggle is providing 6 monetary prizes for the best data storytelling submissions. More information on the competition, data, and prizes can be found on:
https://www.kaggle.com/kaggle/kaggle-survey-2018
The dataset provided (Kaggle_Salary.csv) in Assignment 2 contains a modified version of the survey results provided by Kaggle in the file mutiplechoiceResponses.csv. The survey results from 15429 participants are shown in 395 columns, representing survey questions. Not all questions are answered by each participant, and responses contain various data types.
In the dataset for Assignment 2, Q9 “What is your current yearly compensation (approximate $USD)?” has been modified from a range to an integer to be used for regression. This has been done by replacing the compensation range with a random integer from a uniform distribution within that range. Rows with null values or undisclosed salaries have been dropped. For this assignment, only the file Kaggle_Salary.csv can be used. The column “Q9” contains the target variable, and an index column “index” has been added.
The purpose of this assignment is to
1) understand and explore employment in the data science community, as represented in a survey conducted by Kaggle.
2) train, validate, and tune multiple regressors that can predict, given a set of survey responses by a data scientist, what a survey respondent’s current yearly compensation is.

Please download the datafile from the link below . I cannot upload to github since the file is 29+MB.
https://drive.google.com/open?id=1pTLn8nn3ZsQRLJaQ_C8pXadSxOQ6jL0Q
