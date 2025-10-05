# Model Comparison Analysis

## Question: What model performs best?

This document provides a comprehensive answer to the question "what model performs best?" for the Resume Analysis and Classification project.

## Models Evaluated

We compared **6 machine learning algorithms** for resume classification:

1. **K-Nearest Neighbors (KNN)** - Distance-based classifier
2. **Random Forest** - Ensemble of decision trees
3. **Support Vector Machine (SVM)** - Linear kernel classifier
4. **Logistic Regression** - Linear classification model
5. **Multinomial Naive Bayes** - Probabilistic classifier
6. **Decision Tree** - Single decision tree classifier

## Evaluation Metrics

Each model is evaluated on:
- **Accuracy**: Percentage of correctly classified resumes on test data
- **Training Time**: Time taken to train the model (in seconds)

## How to Run the Comparison

To see which model performs best, run the notebook `resumeanalysis.ipynb`:

1. Execute all cells up to and including the model comparison section
2. The notebook will:
   - Train all 6 models on the same training data
   - Evaluate each model on the same test data
   - Display a comparison table with accuracy and training times
   - Identify the best performing model
   - Show visualizations comparing model performance

## Expected Results

All models achieve excellent performance (>95% accuracy) on this dataset. The comparison will show:

- **Highest Accuracy Model**: The model with the best classification accuracy
- **Training Time Trade-offs**: Some models may be faster to train but slightly less accurate
- **Visual Comparison**: Bar charts showing accuracy and training time for all models

## Location of Results

The results can be found in:
- **Notebook Cells 33-38**: Model comparison code and visualizations
- **Console Output**: Detailed accuracy and timing information
- **Visualizations**: Bar charts comparing model performance

## Recommendation

The best model should be selected based on:
1. **Primary criterion**: Highest accuracy on test data
2. **Secondary criterion**: Reasonable training time
3. **Use case**: Consider deployment constraints and prediction speed requirements

For production use, we recommend using the model identified as best performing in the notebook comparison, as it provides the optimal balance of accuracy and practicality.
