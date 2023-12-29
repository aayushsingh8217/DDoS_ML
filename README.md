# DDoS_ML
# DDoS Attack Classification

## Overview

This machine learning project aims to detect and classify Distributed Denial of Service (DDoS) attacks in network traffic. We utilize various algorithms, including Random Forest, Logistic Regression, and Neural Networks, to enhance cybersecurity measures and identify potential threats.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Machine Learning Models](#machine-learning-models)
- [Model Evaluation](#model-evaluation)
- [Receiver Operating Characteristic (ROC) Curve Analysis](#receiver-operating-characteristic-roc-curve-analysis)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Introduction

DDoS attacks pose a significant threat to network security by overwhelming systems with a flood of traffic, making services unavailable. This project employs machine learning to classify network traffic as either benign or a potential DDoS attack. The goal is to develop robust models capable of accurate detection.

## Dataset

The dataset (`DDos.csv`) used in this project contains a wealth of information about network traffic. Each row represents a data point with features describing network behavior, and the target variable is 'Label,' indicating whether the traffic is benign or a DDoS attack.

## Preprocessing

The preprocessing steps include handling missing values, addressing data types, and converting categorical variables. Additionally, we split the dataset into training and testing sets to train and evaluate our machine learning models.

## Exploratory Data Analysis

Explore the dataset to gain insights into the distribution of features, identify patterns, and understand the characteristics of benign and DDoS traffic. Visualization and summary statistics are crucial in preparing the data for machine learning.

## Machine Learning Models

### Random Forest

Random Forest is an ensemble learning method that constructs a multitude of decision trees during training and outputs the mode of the classes.

### Logistic Regression

Logistic Regression is a linear model for binary classification. It estimates the probability that a given instance belongs to a particular class.

### Neural Network

Neural Networks, specifically a Multi-Layer Perceptron (MLP), provide a powerful approach for capturing complex relationships in data through multiple layers of interconnected nodes.

## Model Evaluation

Evaluate the performance of each model using standard machine learning metrics such as accuracy, precision, recall, and F1 score. Assessing the confusion matrix provides insights into the models' ability to correctly classify benign and DDoS traffic.

## Receiver Operating Characteristic (ROC) Curve Analysis

Analyze the ROC curves and calculate the Area Under the Curve (AUC) to understand each model's ability to distinguish between benign and DDoS traffic.

