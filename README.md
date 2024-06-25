# Machine Learning Based Approach For Hope Speech Detection
This is the code that I have used to participate in IberLEF 2024 in a subtask - "Hope for Equality, Diversity and Inclusion" of the shared task.
I have trained 4 machine learning models and 2 BERT models.

## Preprocessing and training:
First encoding of the categorical variables is done. TF-IDF vectorizer is used to convert the textual data to numeric format.
I used K-Fold cross validation for machine learning models and train test split for BERT models.

## Result
Bert model 1, logistic regression and MultinomialNB performed well on test data. Logsitic regresion had F1- score of 0.4161 and secured 15th place.
