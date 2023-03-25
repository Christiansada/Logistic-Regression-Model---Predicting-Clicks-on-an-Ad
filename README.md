# Logistic-Regression-Project---Predicting-Clicks-on-an-Ad
This project is an implementation of logistic regression to predict whether or not an internet user clicked on an advertisement on a company website. The data set includes various features of the user such as age, gender, income, and internet usage, which are used to train the model to predict whether the user will click on an ad or not.
### Data Set
The data set used in this project is a fake advertising data set, containing the following features:

- 'Daily Time Spent on Site': consumer time on site in minutes
- 'Age': customer age in years
- 'Area Income': Avg. Income of geographical area of consumer
- 'Daily Internet Usage': Avg. minutes a day consumer is on the internet
- 'Ad Topic Line': Headline of the advertisement
- 'City': City of consumer
- 'Male': Whether or not consumer was male
- 'Country': Country of consumer
- 'Timestamp': Time at which consumer clicked on Ad or closed window
- 'Clicked on Ad': 0 or 1 indicated clicking on Ad

### Implementation
The logistic regression algorithm is implemented in Python using the scikit-learn library. The data is first preprocessed, including one-hot encoding of categorical features and scaling of numerical features. The preprocessed data is then split into training and testing sets, with a ratio of 67:33. The logistic regression model is trained on the training set and evaluated on the testing set.

### Results
The logistic regression model achieved an overall accuracy of 91%, with a precision of 87% and recall of 96% for the class 0, and a precision of 96% and recall of 86% for the class 1. This indicates that the model is performing well in predicting both the positive and negative class.

### Conclusion
The logistic regression model was successfully implemented to predict whether an internet user clicked on an advertisement on a company website. The model achieved good performance, which can be further improved by fine-tuning the hyperparameters and exploring other classification algorithms.



