# Machine Learning: FIFA 2018 Man of the Match Prediction

A comprehensive machine learning project that predicts the "Man of the Match" award winners from FIFA 2018 World Cup match statistics using Random Forest classification.

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0.19+-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## Project Overview

This project demonstrates the application of machine learning techniques to sports analytics, specifically predicting Man of the Match recipients based on in-game performance statistics. The analysis uses a comprehensive dataset from the FIFA 2018 World Cup, implementing Random Forest classifiers with hyperparameter optimization.

## Dataset

- **Source**: FIFA 2018 World Cup Statistics
- **Size**: 128 observations, 27 features
- **Target Variable**: Man of the Match (binary classification)
- **Features Include**: Team statistics, goals scored, attempts, possession, passes, and various performance metrics

## Key Features

- **Data Preprocessing**: Comprehensive data cleaning and feature engineering
- **Random Forest Classification**: Both baseline and optimized models
- **Hyperparameter Tuning**: RandomizedSearchCV for model optimization
- **Comprehensive Evaluation**: Multiple metrics including accuracy, precision, recall, F1-score, and ROC-AUC
- **Visualization**: ROC curves and confusion matrices for model interpretation

## Technologies & Libraries

- **Core ML**: scikit-learn (RandomForestClassifier, train_test_split, metrics)
- **Data Processing**: pandas, numpy
- **Visualization**: matplotlib, seaborn
- **Statistical Analysis**: pandas-profiling
- **Optimization**: scipy.stats for parameter distributions

## Project Structure

```
MachineLearning/
+-- FIFA_2018_Statistics_project_term_2_Ravi_and_Paras.ipynb  # Main analysis notebook
+-- Term2_Project_FIFA_2018.pptx                            # Project presentation
+-- Term2_Project_Presentation.mp4                           # Video presentation
+-- README.md                                                # This file
```

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- pip package manager

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RaviGit18/MachineLearning.git
   cd MachineLearning
   ```

2. **Install required packages:**
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn pandas-profiling jupyter
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Open and run the analysis:**
   - Navigate to `FIFA_2018_Statistics_project_term_2_Ravi_and_Paras.ipynb`
   - Execute cells sequentially to reproduce the complete analysis

## Model Performance

The project implements and compares two Random Forest models:

### Baseline Model
- Standard Random Forest with default parameters
- Comprehensive evaluation using multiple metrics

### Optimized Model
- Hyperparameter tuning using RandomizedSearchCV
- Improved performance through parameter optimization

### Evaluation Metrics
- **Accuracy Score**: Overall model correctness
- **Precision Score**: True positive prediction accuracy
- **Recall Score**: Sensitivity to positive cases
- **F1-Score**: Harmonic mean of precision and recall
- **ROC-AUC**: Model discriminative ability
- **Confusion Matrix**: Detailed classification results

## Analysis Pipeline

1. **Data Loading & Exploration**: Dataset import and initial analysis
2. **Preprocessing**: Feature selection and data preparation
3. **Model Training**: Random Forest implementation
4. **Baseline Evaluation**: Initial model performance assessment
5. **Hyperparameter Optimization**: RandomizedSearchCV implementation
6. **Advanced Evaluation**: Comprehensive metric analysis
7. **Visualization**: ROC curves and performance comparisons

## Key Insights

- Demonstrates practical application of classification algorithms
- Shows importance of hyperparameter tuning in model performance
- Provides comprehensive evaluation framework for binary classification
- Illustrates sports analytics use case in machine learning

## Authors

- **Ravi** - Initial implementation and analysis
  - LinkedIn: https://www.linkedin.com/in/ravi-ranjan-tech/
- **Paras** - Collaborative development and presentation
  - LinkedIn: https://www.linkedin.com/in/paras-prakash-5130332b/

## References

- scikit-learn Documentation: https://scikit-learn.org/
- FIFA 2018 World Cup Statistics Dataset
- INSAID Course Materials and Guidelines
