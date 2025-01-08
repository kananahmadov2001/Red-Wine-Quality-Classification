<div align="center">
    <h1 id="Header">Red Wine Quality Classification</h1>
</div>

## Overview
This project focuses on applying machine learning techniques to predict red wine quality based on physicochemical attributes. Using the Red Wine Quality Dataset from the UCI Machine Learning Repository, the project leverages three classification models: Support Vector Machine (SVM), Artificial Neural Network (ANN), and K-Nearest Neighbors (KNN), to identify the strengths and limitations of each approach.

## Features
- **Data Preprocessing:**
  - Standardization of input features for consistent scaling.
  - Feature selection using **Information Gain** to reduce dimensionality and improve model performance.
  
- **Machine Learning Models:**
  - **SVM:** Utilizes hyperplanes for classification with fine-tuned hyperparameters.
  - **ANN:** A multi-layer perceptron designed to capture complex, non-linear relationships.
  - **KNN:** Leverages proximity-based predictions with optimal neighbor selection.

- **Evaluation Metrics:**
  - Models evaluated using **Accuracy**, **Precision**, **Recall**, **F1-Score**, and **Confusion Matrices**.
  - Visualizations of results to compare model performance.

## Results
- **ANN:** Achieved the best performance with an accuracy of 66% and higher weighted average scores across all metrics.
- **KNN:** Performed second best with an accuracy of 62%, benefiting from its proximity-based approach.
- **SVM:** Achieved an accuracy of 61% but struggled with minority classes due to class imbalance.

## Technologies and Tools
- **Languages:** Python
- **Libraries:** scikit-learn, matplotlib, pandas, seaborn, numpy
- **Techniques:** Data Standardization, Feature Selection, GridSearchCV, Cross-Validation
- **Visualizations:** Confusion Matrices, Feature Distributions, Classification Reports

## Want to Learn More?
If you want to dive deeper into the details of our project, including methodology, results, and analysis, check out the following pdf in this REPO:
```
Classification_of_Red_Wine_Quality.pdf
```
