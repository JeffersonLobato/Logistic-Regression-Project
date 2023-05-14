# Logistic Regression for Online Ad Click Prediction

This project was developed by Jefferson Lobato during the Data Science and Machine Learning course at Asimov Academy. To learn more about Asimov Academy, visit the website https://asimov.academy/.

The objective of this project is to create a logistic regression model that predicts whether an internet user will click on an ad based on demographic and online behavior data.

## Data

The data contains information such as time spent on the website, age, average income of the region, daily internet usage, ad title, city, country, gender, and whether the user clicked on the ad or not. The dataset is fictitious and created for learning and testing purposes.

## Technologies Used

- Pandas
- NumPy
- Seaborn
- Matplotlib.pyplot
- Train_test_split
- LogisticRegression
- GridSearchCV
- Accuracy_score
- Confusion_matrix
- Classification_report

## Methodology

The methodology used to create the logistic regression model consisted of:

1. Data exploration: exploratory analysis of the data to identify possible relationships between variables and verify data quality.
2. Data preprocessing: handling missing values, encoding categorical variables, and scaling numerical data.
3. Model creation: creation of the logistic regression model using the Scikit-learn library.
4. Model training and tuning: dividing the data into training and testing sets, tuning the model's hyperparameters using cross-validation with GridSearchCV.
5. Model evaluation: evaluating the performance of the model using metrics such as accuracy, precision, recall, and F1-score.

## Results

The created logistic regression model achieved an accuracy of 98% in predicting online ad clicks. The confusion matrix showed that the model performed well in classifying users who clicked on the ad as well as those who did not.

## Conclusion

The logistic regression model proved to be an effective approach in predicting online ad clicks based on demographic and online behavior data. However, it is important to note that the data used in this project is fictitious, and the model may not perform as well on real data. Additionally, it is important to evaluate other modeling approaches and consider other variables to obtain an even more accurate and robust model.