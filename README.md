# dropout-analysis 📚

## About
This is our (B128 Team 8) mini-project for SC1015 Data Science & Artificial Intelligence.<br>
The aim of our project is to create a model that predicts whether a student is likely to drop out of school based on certain variables. The purpose of predicting the main factors behind a student dropping out is to help schools better identify at-risk students and provide interventions to improve student retention.<br>
Our dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention). Our source code can be viewed here [WIP]().

## Contributors
- Nicholas (@nicholasbay)
- Qian Yu
- Ayman

## Problem Definition
To predict whehter a student will drop out based on a combination of the following variables:
1. whether they are paying their tuition fees timely ("Tuition fees up to date")
2. whether they are a scholarship holder ("Scholarship holder")
3. their gender ("Gender")
4. their age at enrollment ("Age at enrollment")

## Technology Used
- Python
- Pandas: For data cleaning and processing
- Seaborn: For data visualisation
- Matplotlib: For data visualisation
- SciPy: For statistical analysis
- NumPy: For numerical comptuing

## Methodology
Our project was completed in several stages, including data processing, model selection, and model evaluation.
### Data processing:
- Exploratory data analysis
- Data cleaning
### Model selection:
- Train-test split with class imbalances corrected
- Hyperparameter tuning
- Random Forest Classifier
- Model tuning
### Model Evaluation:
- Precision score
- F-score
- Confusion matrix

## Conclusion
After evaluating several models, the best model was able to predict student drop out with a precision of 0.77992 and F-score of 0.77783. The most important feature for predicting student dropout was "Tuition fees up to date".

## What did we learn from this project?
- Concepts of Chi-Square Test, Precision, Recall, and F-score
- Handling imbalanced classes using the ```stratify``` parameter in ```train_test_split```
- Hyperparameter tuning
- Random Forest Classifier from sklearn

## References
1. Realinho, V., Machado, J., Baptista, L., &amp; Martins, M. V. (2022). Predicting student dropout and academic success. Data, 7(11). https://doi.org/10.3390/data7110146

2. Hashmi, F. (2021) How to measure the correlation between two categorical variables in Python, Thinking Neuron. Available at: https://thinkingneuron.com/how-to-measure-the-correlation-between-two-categorical-variables-in-python/