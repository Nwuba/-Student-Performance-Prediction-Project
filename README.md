# Student Performance Prediction Project

## Overview

This project aims to analyze and predict student performance based on various factors such as hours studied, previous scores, sleep hours, and the number of sample question papers practiced. The project utilizes Python's data science libraries to preprocess the data, create visualizations, and build a linear regression model to predict student performance.

## Project Structure

- **Data Wrangling**: The project starts with reading and preprocessing the dataset. Missing values are handled using the `SimpleImputer` from Scikit-learn.
  
- **Data Visualization**: A 3D scatter plot is created using Plotly to visualize the relationship between the number of hours studied, previous scores, and the performance index.

- **Model Training**: A linear regression model is trained on the dataset to predict the performance index. The model's performance is evaluated using Mean Absolute Error (MAE).

## Installation

To run this project, you need to have the following libraries installed:

```bash
pip install numpy pandas scikit-learn plotly
