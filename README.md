# Data-Analytics

This project helps make prediction for temperature variable. We start from descriptive analysis to deep learning algorithms.
The dataset used here is a time series data, gotten from the Ireland Metrological Service using this website: "https://www.met.ie/climate/available-data/historical-data".

# Descriptive Statistics
Descriptive statistics gives detail summary about the dataset or visual summary of the data for better interpretation. The dataset was split into two categories; numerical and categorical features. Each numeric attributes in the dataset were graphically represented using the differents plots, while the categorical data were graphically represented using majorly bar charts.

# Inferential Statistics
Inferential statistics is to infer the behaviour of the whole dataset from a group of sample data. Pearson’s and Spearman’s correlation was completed on the dataset to determine the linear relationship between each numerical feature.

# Supervised Machine Learning – Regression Methods
Regression methods were performed on the dataset, comparing and analysing the various results from the different regression algorithm used. Regression is categorised under supervised machine learning. There are some similarities with only slight additional modification for the diverse individual models.


Setting up the Machine Learning Model
After exploring the data, the regression model was set up by selecting the features for the prediction, followed by separating the dataset to differentiate the training and testing dataset to predict the temperature label. From the whole dataset, 70% was selected for the data training, and the rest 30% was used for testing, and this enabled evaluation of the model performance. For the splitting of the dataset, the train_test_split function from scikit-learn library was used. The resulting effect of the splitting yielded four separate datasets:
•	X_train: The feature values used to train the model.
•	y_train: The resulting labels used to train the model
•	X_test: The feature values used to validate the model
•	y_test: The resulting labels to validate the model.



# Deep Learning
Long Short-Term Method (LSTM) and Gated Recurrent Units (GRU) model were applied on the testg data varying the numbers of neurons and epochs.


# Running the Code
1. Download the dataset
2. Download the files
3. Save the dataset in a folder
4. Change the directive in both codes


NB: Codes is preferable to be run on Google Colab, because it is faster and easier to save dataset on your Google Drive.
