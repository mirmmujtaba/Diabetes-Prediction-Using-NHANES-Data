# Diabetes-Prediction-Using-NHANES-Data
This repository contains the implementation of a binary classification model to predict the presence of diabetes using the National Health and Nutrition Examination Survey (NHANES) 2017-2018 data.

# Project Overview
The goal of this project is to predict the presence of diabetes in individuals based on various demographic, laboratory, and medical examination features collected by NHANES. The binary classification model utilizes the 'DIQ010' column as the target variable, which indicates whether an individual has diabetes or not.

# Dataset
The dataset used in this project is collected from the National Health and Nutrition Examination Survey (NHANES) 2017-2018 cycle. NHANES is a major program of the National Center for Health Statistics (NCHS) and is designed to assess the health and nutritional status of adults and children in the United States.

# Features and Preprocessing
The NHANES 2017-2018 dataset contains numerous features related to demographics, laboratory tests, and medical examinations. To preprocess the dataset and prepare it for machine learning, the following steps were performed:
1.	Merge the demographic, laboratory, and medical examination data.
2.	Handle missing values by dropping columns with a high percentage of missing values and imputing the remaining missing values.
3.	Scale numerical features using standardization.

# Model
A RandomForestClassifier is used to predict the presence of diabetes based on the selected and preprocessed features from the NHANES dataset. Hyperparameters of the model are optimized using the HyperOpt library.

# Evaluation Metric
The primary evaluation metric used for assessing the performance of the binary classification model is the F1 score, which is the harmonic mean of precision and recall. The F1 score ranges between 0 and 1, with 1 being the best possible score.
