# YouTube Comment Sentiment Analysis


## Overview
This project aims to classify YouTube comments into six sentiment classes: Positive, Negative, Corrective, Interrogative, Imperative, and Neutral. The dataset is preprocessed to remove punctuation, multiple spaces, and uses part-of-speech tagging and lemmatization. SMOTE (Synthetic Minority Over-sampling Technique) is used for balancing the dataset, and TF-IDF (Term Frequency-Inverse Document Frequency) is used for feature extraction. Six machine learning models are trained and their performances are evaluated.

## Dataset
- **Classes**: 6 (Positive, Negative, Corrective, Interrogative, Imperative, Neutral)
- **Data Preprocessing**:
  - **Punctuation Removal**: Removes punctuation marks from the comments.
  - **Multiple Spaces Removal**: Cleans up extra spaces in the comments.
  - **Part-of-Speech Tagging (POS Tagger)**: Tags each word with its corresponding part of speech.
  - **Lemmatization**: Reduces words to their root forms for normalization.
  - **SMOTE**: Balances the dataset by oversampling the minority classes.

## Feature Extraction
- **TF-IDF**: Converts the text data into numerical features, where each term's weight reflects its importance within a document relative to the entire corpus.

## Model Training and Evaluation
The following machine learning models were trained and evaluated:
- **Naive Bayes (NB)**
- **Decision Tree (DT)**
- **Random Forest (RF)**
- **Logistic Regression (LR)**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**

## Model Evaluation
The performance of each model is evaluated using the following metrics:
- **Accuracy**: The ratio of correctly predicted instances to the total instances.
- **Precision**: The ratio of true positive predictions to the total predicted positives.
- **Recall**: The ratio of true positive predictions to all actual positives.
- **F1 Score**: The harmonic mean of precision and recall.
- **Confusion Matrix**: A table used to describe the performance of the classification model on a set of test data for which the true values are known.
- **ROC Curve**: A graphical plot that illustrates the diagnostic ability of a binary classifier system as its discrimination threshold is varied.

## Results
### Precision, Recall, and F1-Score Comparison
- ![Precision, Recall, F1-Score Comparison](https://i.ibb.co/Wnvmkwd/mx.png)

### ROC Curve
- ![ROC Curve](https://i.ibb.co/VwmDp2q/my.png)

### Classifier Accuracy by Class
- ![Classifier Accuracy by Class](https://i.ibb.co/5rtJ16F/mz.png)

