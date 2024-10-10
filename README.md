# Interactive Web App with Streamlit and Scikit-learn
This project is an interactive web application built with Streamlit and Scikit-learn. It allows users to explore and apply machine learning algorithms on well-known datasets like Iris, Wine, and Breast Cancer. Users can upload their own datasets, select a machine learning algorithm, and obtain predictions with real-time performance metrics. The app demonstrates how easily machine learning models can be integrated into a web interface for educational purposes or practical use cases. See official [streamlit website](https://www.streamlit.io/) for more info.

## Preview
![Example of Streamlit|635x380](data/example.gif)

## Installation
You need these dependencies:
```console
pip install streamlit
pip install scikit-learn
pip install matplotlib
```

## Usage
Run
```console
streamlit run main.py
```

## Datasets
### Iris Dataset: Classify iris species using sepal and petal measurements.
### Wine Dataset: Predict wine cultivar based on chemical properties.
### Breast Cancer Dataset: Classify tumors as malignant or benign using cell nucleus features.

## Algorithms
### K-Nearest Neighbors (KNN): Classifies based on proximity to nearest data points.
### Random Forest: An ensemble of decision trees to improve prediction accuracy.
### Support Vector Machines (SVM): Finds the optimal hyperplane to separate classes.
