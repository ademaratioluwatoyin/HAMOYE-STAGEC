# HAMOYE-STAGEC
MACHINE LEARNING: CLASSIFICATION - MANAGING THE QUALITY METRIC OF GLOBAL ECOLOGICAL FOOTPRINT
School Avatar	
OneSchool
SHARE
  
Read Reviews
Machine Learning: Classification - Managing the Quality Metric of Global Ecological Footprint
Difficulty levels: College, Graduate School, Professional
The dataset used in this course was obtained from the National Footprint and Biocapacity Accounts. It provides Ecological Footprint per capita data for years 1961-2016 in global hectares (gha). The National Footprint and Biocapacity Accounts (NFAs) measure the ecological resource use and resource capacity of nations from 1961 to 2016. The calculations in the National Footprint and Biocapacity Accounts are primarily based on United Nations data sets.

In this course, we will use the data to classify and predict the quality metrics (qascore) of the ecological footprint data for the different countries. This data includes total and per capita national biocapacity, the ecological footprint of consumption, the ecological footprint of production and total area in hectares.

Data Source: https://data.world/footprint/nfa-2019-edition

Duration:  14 days
Enrolled
Discuss
Study Groups

Follow
Machine Learning: Classification - Managing the Quality Metric of Global Ecological Footprint
Teachers
Hamoye Six, Hamoye One, Hamoye Two, Hamoye Nine

Students Information
Students currently enrolled: 832

Students completed the course: 563

Lessons
Lesson 1
Linear Classification and Logistic Regression
Duration: 2 days
About The Lesson
In this lesson, you will learn about linear classification.

In machine learning, classification is a supervised method of segmenting data points into various labels or classes. Unlike regression, the target variable in a classification problem is discrete. Each data point used in training classification models must have a corresponding label in order for the characteristics and patterns in the classes to be learnt appropriately. Classification can either be binary - identifying that a given email is spam or not or, multi-class - classifying a fruit as orange, mango or banana.

All codes used in this lesson can be found here.

Resources
TEXT
Introduction
TEXT
Linear Classification and Logistic Regression
PDF
Code Snippet_1.pdf
Lesson 2
Measuring Classification Performance
Duration: 5 days
About The Lesson
In this lesson, you will learn about cross validation techniques used by data scientist to avoid overfitting and enable generalization.

All codes used in this lesson can be found here.

Resources
TEXT
Measuring Classification Performance
PDF
Code Snippet_2.pdf
Lesson 3
Multiclass Classification
Duration: 1 day
About The Lesson
In this lesson, you will learn how to deal with more than two classes where an instance is classified into a single class.

Resources
TEXT
Multiclass Classification
Lesson 4
Tree-Based Methods and The Support Vector Machine
Duration: 3 days
About The Lesson
In this lesson, you will learn about Support Vector Machine (SVM), a supervised machine learning algorithm that is used to solve both classification and regression tasks.

All codes used in this lesson can be found here.

Resources
TEXT
Tree-Based Methods and The Support Vector Machine
Lesson 5
Ensemble Methods
Duration: 5 days
About The Lesson
In this lesson, you will learn how to combine several classifiers to obtain an optimal model with better performance as opposed to just a single classifier.

Resources
TEXT
Ensemble Methods
TEXT
Additional Reading Resources
PDF
Code Snippet_5.pdf
Lesson 6
Graded Quiz
Duration: 5 days
About The Lesson
Congratulations on successful course completion!
See instructions in the resource below to guide you in taking your final assessment

Resources
TEXT
[IMPORTANT] Instructions
TEXT
Dataset Description
Quiz
Graded Quiz
Duration: 90 minutes
Question count: 20
License 
All Rights Reserved
Recommended Courses
Data Engineering: Setting Up Kubernetes
Data Engineering: Setting Up Kubernetes
The world of data engineering is one of utmost importance as the knowledge of a data engineer is required to build tools, infrastructure, workflows and services that are necessary for data processes.

Data Storytelling in Pattern Recognition
Data Storytelling in Pattern Recognition
This course uses data on food production and consumption in Africa obtained from FAO's resources. The course covers the concepts of pattern recognition and storytelling, and their relationship. Although originally developed using Wolfram Programming…

Python Libraries for Storytelling
Python Libraries for Storytelling
A python library is a reusable chunk of code that can be included in a repository while writing codes. Python also has its inbuilt library known as the standard library, with over 200 modules. Python also has an amazingly large collection of libraries…

Kubeflow Components &  Pipelines
Kubeflow Components &  Pipelines
In today's world  of problem solving , it is almost impossible to neglect the significance of kubeflow. Data scientists who want to build and experiment with ML pipelines, ML engineers and operational teams who want to deploy ML systems to various…

Hamoye Career Incubator ML Fullstack Program [Premium Plan]
Hamoye Career Incubator ML Fullstack Program [Premium Plan]
Welcome to Hamoye’s Career Incubator Program: ML Fullstack Program (Advanced tier)

Becoming a Data Storyteller
Becoming a Data Storyteller
In this course, you will learn the basics of technical writing, and how to become technical writers. This course will outline and define the technical writing process, best practices, and steps to launch a technical writing career.

Hamoye Career Incubator ML Fullstack Program [Premium Plan]
Hamoye Career Incubator ML Fullstack Program [Premium Plan]
Welcome to Hamoye’s Career Incubator Program: ML Fullstack Program (Advanced tier)

Hamoye Career Incubator: ML Fullstack Program [Standard Plan]
Hamoye Career Incubator: ML Fullstack Program [Standard Plan]
Welcome to Hamoye’s Career Incubator: ML Fullstack Program (Advanced tier)

Hamoye Career Incubator: ML Fullstack Program [Standard Plan]
Hamoye Career Incubator: ML Fullstack Program [Standard Plan]
Welcome to Hamoye’s Career Incubator: ML Fullstack Program (Advanced tier)

Introduction to Kubernetes
Introduction to Kubernetes
In this course, we will explore what kubernetes is, its architecture and building blocks, how it can be run on our local system or in the cloud, different ways we can configure and protect sensitive information, and how we can let external applications…



Dataset Description
Stability of the Grid System
Electrical grids require a balance between electricity supply and demand in order to be stable. Conventional systems achieve this balance through demand-driven electricity production. For future grids with a high share of inflexible (i.e., renewable) energy source, the concept of demand response is a promising solution. This implies changes in electricity consumption in relation to electricity price changes. In this work, we’ll build a binary classification model to predict if a grid is stable or unstable using the UCI Electrical Grid Stability Simulated dataset.

Dataset: https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+

It has 12 primary predictive features and two dependent variables.

Predictive features:

'tau1' to 'tau4': the reaction time of each network participant, a real value within the range 0.5 to 10 ('tau1' corresponds to the supplier node, 'tau2' to 'tau4' to the consumer nodes);
'p1' to 'p4': nominal power produced (positive) or consumed (negative) by each network participant, a real value within the range -2.0 to -0.5 for consumers ('p2' to 'p4'). As the total power consumed equals the total power generated, p1 (supplier node) = - (p2 + p3 + p4);
'g1' to 'g4': price elasticity coefficient for each network participant, a real value within the range 0.05 to 1.00 ('g1' corresponds to the supplier node, 'g2' to 'g4' to the consumer nodes; 'g' stands for 'gamma');
Dependent variables:

'stab': the maximum real part of the characteristic differential equation root (if positive, the system is linearly unstable; if negative, linearly stable);
'stabf': a categorical (binary) label ('stable' or 'unstable').
Because of the direct relationship between 'stab' and 'stabf' ('stabf' = 'stable' if 'stab' <= 0, 'unstable' otherwise), 'stab' should be dropped and 'stabf' will remain as the sole dependent variable (binary classification).

Split the data into an 80-20 train-test split with a random state of “1”. Use the standard scaler to transform the train set (x_train, y_train) and the test set (x_test). Use scikit learn to train a random forest and extra trees classifier. And use xgboost and lightgbm to train an extreme boosting model and a light gradient boosting model. Use random_state = 1 for training all models and evaluate on the test set.

Also, to improve the Extra Trees Classifier, you will use the following parameters (number of estimators, minimum number of samples, minimum number of samples for leaf node and the number of features to consider when looking for the best split) for the hyperparameter grid needed to run a Randomized Cross Validation Search (RandomizedSearchCV).

n_estimators = [50, 100, 300, 500, 1000]

min_samples_split = [2, 3, 5, 7, 9]

min_samples_leaf = [1, 2, 4, 6, 8]

max_features = ['auto', 'sqrt', 'log2', None]

hyperparameter_grid = {'n_estimators': n_estimators,

'min_samples_leaf': min_samples_leaf,

'min_samples_split': min_samples_split,

'max_features': max_features}
