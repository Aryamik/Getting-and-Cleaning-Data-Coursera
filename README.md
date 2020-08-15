# Getting-and-Cleaning-Data-Coursera

# Coursera *Getting and Cleaning Data* course project

One of the most exciting areas in all of data science right now is wearable computing - see for example [this article](http://www.insideactivitytracking.com/data-science-activity-tracking-and-the-battle-for-the-worlds-top-sports-brand/). Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users.

In this project, data collected from the accelerometer and gyroscope of the Samsung Galaxy S smartphone was retrieved, worked with, and cleaned, to prepare a tidy data that can be used for later analysis.


This is the course project for the Getting and Cleaning Data Coursera course.

The R script, `run_analysis.R`, does the following:

1. Download the dataset if it does not already exist in the working directory
2. Reading the data
3. Merges the two datasets
4. Extracts only the measurements on the mean and standard deviation for each measurement.
5. Merges the two datasets
6. Uses descriptive activity names to name the activities in the data set.
7. Appropriately labels the data set with descriptive variable names.
8. Creates a second, independent tidy set with the mean of each variable for each activity and each subject.

The end result is shown in the file `tidy_data.txt`.

The codebook, `CodeBook.md`, describes the variables, the data, and any 
transformations or work that was performed to clean up the data. 

