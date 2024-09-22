# Comparison of the Naïve Bayes Algorithm and Support Vector Machine (SVM) in the Sentiment Analysis of Twitter Social Media Users towards PT Esteh Indonesia Makmur

This repository contains a python project for sentiment analysis, which classifies text as positive and negative. The project is designed to be run on Google Colab, making it easy to set up and run without local installation.

### Features
- Scraping and labeling manual
- Pre-Processing (Cleansing, Case Folding, Normalization, Tokenizing, Stopword, Stemming)
- TF-IDF
- Oversampling (SMOTE)
- Modelling using Naive Bayes and Support Vector Machine
- Model evaluation using metrics such as accuracy, precision, recall, F1-score, AUC-ROC, and AUC-PR

### Usage in Google Colab
To run this project in Google Colab, follow these steps:
1. Open the Google Colab notebook for this project.
2. Ensure the necessary libraries are installed. In the first cell of the notebook, you will find installation commands for any required libraries, such as:
   ```bash
   !pip install demoji
   !pip install sastrawi
   !pip install imbalanced-learn
   !pip install scikit-learn
4. Upload your dataset to Colab or use the default dataset provided in the notebook.
5. Run the notebook step by step by pressing Shift + Enter on each cell to execute the code or pressing Ctrl + F9 to run all code.

### Dataset
The dataset was obtained from X (Twitter) using the scraping method with the snscrape library. The data consists of tweets containing the keywords "es teh indonesia" and "somasi" collected within the timeframe of September 24-30, 2022.

### Model
- Naive Bayes Without Hyperparameter Tuning
- Naive Bayes With Hyperparameter Tuning
- Support Vector Machine Without Hyperparameter Tuning
- Support Vector Machine With Hyperparameter Tuning

### Results
| Model | Accuracy | Precision | Recall | F1-Score | AUC-ROC | AUC-PR
|:--------|---------|---------| ---------| ---------| ---------| ---------|
| NB Without Tuning  | 80,26%  | 62,80%  | 73,92%  | 64,83%  | 0,8  | 0,45  |
| NB With Tuning  | 85,45%  | 65,37% | 70,38%  | 67,26%  | 0,77  | 0,37 |
| SVM Without Tuning  | 90,39%  | 78,91%  | 59,17%  | 62,51%  | 0,85  | 0,42 |
| SVM With Tuning  | 90,39%  | 82,86%  | 57,03%  | 59,68%  | 0,79  | 0,37 |

Based on the table, overall the SVM algorithm without hyperparameter tuning performs better than Naive Bayes algorithm.

