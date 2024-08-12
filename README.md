# Student Performance Prediction

This project uses machine learning to predict student performance based on various factors such as study hours, previous scores, extracurricular activities, sleep hours, and practice with sample question papers.

## Table of Contents
- [Overview](#overview)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Model](#model)
- [Usage](#usage)
- [Results](#results)

## Overview

This Jupyter Notebook demonstrates the process of building a multi-linear regression model to predict student performance. It covers data preprocessing, model creation, training, and evaluation.

## Dependencies

The project requires the following Python libraries:
- pandas
- torch (PyTorch)
- matplotlib
- numpy

You can install these dependencies using pip:

```
pip install pandas torch matplotlib numpy
```

## Dataset

The dataset used in this project is stored in 'Student_Performance.csv'. It includes the following features:
- Hours Studied
- Previous Scores
- Extracurricular Activities
- Sleep Hours
- Sample Question Papers Practiced

The target variable is the Performance Index.

## Model

The project implements a Multi-Linear Regression model using PyTorch. The model architecture is defined in the `MLR` class.

## Usage

1. Ensure all dependencies are installed.
2. Place the 'Student_Performance.csv' file in the same directory as the Jupyter Notebook.
3. Run the Jupyter Notebook cells sequentially.

The notebook includes the following main steps:
1. Data loading and preprocessing
2. Data normalization
3. Splitting data into training and test sets
4. Model definition and initialization
5. Model training
6. Model evaluation

## Results

The model's performance is evaluated using the L1Loss (Mean Absolute Error). The training process prints out the loss for both training and test sets every 100 epochs.

After training, the model's predictions are plotted against the actual values for visual comparison.

Feel free to modify the hyperparameters or model architecture to improve performance.
