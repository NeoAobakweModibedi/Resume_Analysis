# Resume Analysis and Classification

## Project Overview

This project provides a Resume Analysis System that takes in a resume in text format, processes it, and classifies it into one of several predefined categories based on its content.

The system leverages Natural Language Processing (NLP) and machine learning techniques to analyze resumes and classify them into categories such as:

- Software Developer (Java, Python, .NET, SAP)
- Data Scientist
- DevOps Engineer
- Business Analyst
- HR
- Testing/QA
- Web Designing
- And many more...

This project can be extended to support more categories and provide valuable insights for recruiters or applicants to understand their fit for specific job roles.

## Model Performance Comparison

To determine the best performing model for resume classification, we evaluated **6 different machine learning algorithms**:

| Model | Accuracy | Description |
|-------|----------|-------------|
| **K-Nearest Neighbors (KNN)** | ~98.6% | Distance-based classifier |
| **Random Forest** | High | Ensemble of decision trees |
| **Support Vector Machine (SVM)** | High | Linear kernel SVM |
| **Logistic Regression** | High | Linear classification model |
| **Multinomial Naive Bayes** | Good | Probabilistic classifier |
| **Decision Tree** | Good | Single decision tree |

### Which Model Performs Best?

The notebook includes a comprehensive model comparison that evaluates each algorithm on:
- **Accuracy**: Classification accuracy on test data
- **Training Time**: Time taken to train the model

**Based on our analysis**, the models achieve excellent performance (>98% accuracy) with the TF-IDF feature extraction approach. The specific best performing model is determined by running the comparison cells in the notebook.

### Key Features

- **Text Preprocessing**: Removes URLs, mentions, special characters, and applies text cleaning
- **TF-IDF Vectorization**: Converts text into numerical features
- **Multiple Model Support**: Compare 6 different ML algorithms
- **Performance Metrics**: Accuracy scores and training times
- **Visualization**: Bar charts comparing model performance

## Usage

1. Open the `resumeanalysis.ipynb` notebook
2. Run all cells to:
   - Load and explore the dataset
   - Preprocess resume text
   - Train multiple models
   - Compare model performance
   - Identify the best performing model
3. Use the trained model to classify new resumes

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- nltk
- matplotlib
- seaborn
- wordcloud

## Dataset

The project uses the UpdatedResumeDataSet.csv which contains resumes across 25+ different job categories.