Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course. The R script, run_analysis.R, does the following:

    Download the dataset if it does not already exist in the working directory
    Load the activity,subject info
    Loads both the training and test features datasets -
   Combines these 3 datasets by rows. So we get 3 dataset of 10299 rows 
    Merges the three datasets by columns to get a new dataset of 10299 rows and 563 columns
Give names to all variables in this new dataset using names from Features dataset
Subset Name of Features by measurements on the mean and standard deviation to get a new dataframe as per selected features including subject and Activity variables.
factorize Variable activity in the data frame Data using descriptive activity names from activity label file.
   Converts the activity and subject columns into factors
   Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
The end result is shown in the file tidydata.txt.