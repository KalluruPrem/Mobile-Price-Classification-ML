# Mobile-Price-Classification-ML
Machine learning project classifying mobile phone price ranges using multiple models, pipelines, and hyperparameter tuning with performance comparison.

## Project Overview

This project predicts the price range of mobile phones using machine learning models.

The dataset contains technical specifications of mobile devices such as battery power, RAM, camera quality, and processor features. Based on these inputs, the model classifies phones into different price categories.

## Dataset

The dataset includes features such as:

* Battery power
* RAM
* Internal memory
* Camera specifications
* Screen dimensions
* Connectivity features

Target variable:

* price_range (0 to 3), representing different price categories

## Methodology

The following steps were performed:

1. Loaded and explored the dataset
2. Performed correlation analysis using a heatmap
3. Split the data into training and testing sets
4. Applied feature scaling using StandardScaler (for applicable models)
5. Built multiple machine learning models using pipelines
6. Applied hyperparameter tuning using RandomizedSearchCV
7. Compared model performance
8. Selected the best model

## Models Used

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest Classifier
* Gradient Boosting Classifier
* XGBoost Classifier

## Evaluation Metrics

The models were evaluated using:

* Accuracy Score
* Classification Report (Precision, Recall, F1-score)

The best model was selected based on overall accuracy.

## Results

All models were compared, and the model with the highest accuracy was selected as the final model.


## Visualizations

The project includes:

* Correlation heatmap
* Model comparison chart
* Confusion matrix
* Feature importance plot (for tree-based models)

These visualizations help in understanding both the data and model behavior.

## Cross Validation

Cross-validation was used to ensure that the model generalizes well and performs consistently across different data splits.

## Author
Kalluru Prem
