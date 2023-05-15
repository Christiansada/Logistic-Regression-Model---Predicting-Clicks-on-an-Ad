# Predicting-Clicks-on-an-Ad
This project involves creating a logistic regression model to predict whether an internet user will click on an advertisement on a company website. The dataset used in this project contains information on the daily time spent on the site, age, area income, daily internet usage, gender, country, and timestamp of each user who either clicked on an ad or closed the window.

### Libraries used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

### Getting the Data
- The advertising dataset is read in from a CSV file using pandas and is set to a dataframe called ad_data.

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

### Exploratory Data Analysis
We use seaborn to visualize the data through histograms and jointplots. We create plots showing the age distribution, area income versus age, daily time spent on site versus age, and daily time spent on site versus daily internet usage. Finally, we create a pairplot with hue defined by the 'Clicked on Ad' column feature.

### Train Test Split
We use the train_test_split function from scikit-learn to split the dataset into training and testing sets with a ratio of 67:33. We choose the features Daily Time Spent on Site, Age, Area Income, Daily Internet Usage, and Male to train our model on.

### Logistic Regression Model
We train and fit a logistic regression model on the training set using scikit-learn's LogisticRegression module. The logistic regression model is trained on the training set and evaluated on the testing set. 

### Results
The logistic regression model achieved an overall accuracy of 91%, with a precision of 87% and recall of 96% for the class 0, and a precision of 96% and recall of 86% for the class 1. This indicates that the model is performing well in predicting both the positive and negative class.

### Conclusion
The logistic regression model was successfully implemented to predict whether an internet user clicked on an advertisement on a company website. The model achieved good performance, which can be further improved by fine-tuning the hyperparameters and exploring other classification algorithms.



