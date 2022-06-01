# Project Overview

In this project, we will apply the skills acquired in the [Machine Learning Fundamentals and Decision Trees](https://github.com/ivanovitchm/ppgeecmachinelearning/tree/main/lessons/week_02/sources) lesosn, diven by [Ivanovich Silva](https://github.com/ivanovitchm), to build a classification model using [Prima Indians Diabetes](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) database. All steps of EDA, model training, model testing and others is found in [Machine Learning Fundamentals and Decision Trees for diabetes dataset](https://github.com/mateusArnaudGoldbarg/diabetes_decision_tree).

## Prima Indians Diabetes Dataset

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes based on certain diagnostic measurements (features) of females with at least 21 years old.

The datasets consists of the following features:

- Pregnancies: Number of pregnancies;
- Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test;
- BloodPressure: Diastolic blood pressure (mm Hg);
- SkinThickness: Triceps skin fold thickness (mm);
- Insulin: 2-Hour serum insulin (mu U/ml);
- BMI: Body mass index (weight in kg/(height in m)^2);
- DiabetesPedigreeFunction: Probability of the pacient have diabetes based on family historic;
- Age: Age (years);
- Outcome: Output class variable (0 or 1);

This is an unbalanced dataset, where 268 of 768 are 1 (diabetic), and 500 are 0 (healty).

<center><img width="600" src="https://github.com/mateusArnaudGoldbarg/colab2deploy/blob/main/images/prima.png?raw=true"></center>

## Workflow overview

All the workflow used to build the prediction model followed the good practices of ML workflow as described in the image bellow. The input data came from kaggle, as described before. It was made the Extract, transform and Load (ETL), including data preprocessing and EDA anda data clean. The data was splitted in training and test dataset, and then the traning dataset was divided again in traning and validation dataset for learning purpose. It was made some Hyperparameters tuning to reach the best accuracy as possible. Then, the model was saved as artifact and also used for testing.

<center><img width="800" src="https://github.com/mateusArnaudGoldbarg/colab2deploy/blob/main/images/workflow.png?raw=true"></center>
