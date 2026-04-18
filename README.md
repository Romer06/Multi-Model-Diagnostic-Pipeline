# Multi-Model-Diagnostic-Pipeline

# Multi-Model Diagnostic Pipeline for Heart Disease Prediction

## Overview

This project implements a comprehensive machine learning pipeline to predict heart disease using multiple classification algorithms. The system demonstrates a complete supervised learning workflow, including synthetic data generation, preprocessing, feature scaling, and model evaluation.


## Features

- **Synthetic Data Generation**: Creates a dataset of 300 samples with 13 features representing patient health data.
    
- **Data Preprocessing**: Simulates real-world data challenges by introducing and handling missing values using mean imputation.
    
- **Feature Engineering**: Standardizes input data using `StandardScaler` to improve model convergence.
    
- **Comparative Model Analysis**: Simultaneously evaluates three distinct algorithms to identify the most accurate predictor:
    
    - K-Nearest Neighbors (KNN) 
        
    - Support Vector Machine (SVM) 
        
    - Decision Tree Classifier 
## Tech Stack

- **Language**: Python 
    
- **Libraries**: NumPy, Pandas, Scikit-learn 
    
- **Tools**: Google Colab, GitHub
    
## Implementation Details

The pipeline follows these technical steps as outlined in the implementation manual:

1. **Data Loading**: Generating a synthetic classification dataset with informative and redundant features.
    
2. **Imputation**: Identifying null values in the feature set and replacing them with the attribute mean.
    
3. **Splitting**: Partitioning the dataset into an 80% training set and a 20% testing set.
    

4. **Classification**: Training KNN, SVM, and Decision Tree models on the scaled training data.
    
5. **Evaluation**: Generating accuracy metrics to compare model performance.
    
## Results

The comparative analysis yielded the following performance metrics based on lab results:

- **KNN Accuracy**: 0.916 
    
- **SVM Accuracy**: 0.85 
    
- **Decision Tree Accuracy**: 0.85 
    

The **K-Nearest Neighbors** model demonstrated the highest effectiveness for this specific diagnostic task.

## Conclusion

This project successfully proves that different mathematical approaches to classification yield varying results based on the data distribution. By implementing a multi-model pipeline, we can ensure the selection of the most robust algorithm for healthcare-related predictive tasks.

---

