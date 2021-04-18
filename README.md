# Project: Customer classification using Deep Learning

Project overview:
* In this project, I learned how to perform a customer classification analysis using deep learning
* We want to create a machine learning algorithm based on our available data that can predict if a customer will buy again from the Audiobook company.
* Accurately predicting customer behaviours, allows marketing team to know the customers better, identify their needs and launch targeted ad marketing campaign.
* The data was gathered from an audiobook store

# Code and resources used:
* Python Version: 3.7
* Packages: Pandas | Numpy | Sklearn | TensorFlow2.0
* Data Source: 365 Data Science Complete Program course: https://365datascience.com/courses/

# Data Collection
The data was gathered from an audiobook app and represents 2 years of engagement and 6 months extra of customer conversion to use as targets. In total the data represents 2 years and a half customer engagement

# Data Cleaning:
* After importing the data to a Jupiter notebook, I explored it first with pandas and then divide it into inputs and targets with numpy.
* Balanced the dataset as more than 75% of the target dataset was identified as 0
* Shuffled the data as we will use batches for the deep neural network model
* Split the dataset into train, validation, and test
* Saved the train, validation, and test in .npz format in order to use them with TensorFlow2.0 when creating the model

# Model Building
* Loaded the .npz train, validation and test datasets into the Jupiter notebook
* 	Created the deep neural network with 10 inputs, 2 hidden layers of size 50 and with output size of 2
* 	Optimizer = adam, loss = sparse categorical crossentropy (To apply one-hot-encoding to the targets
* 	Set an early stopping parameter to avoid overfitting




