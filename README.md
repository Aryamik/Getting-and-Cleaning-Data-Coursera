# Getting-and-Cleaning-Data-Coursera

This is the course project for the Getting and Cleaning Data Coursera course.
The R script `run_analysis.R` can be used to create the data set. It retrieves the source data set and transforms it to produce the final data set by implementing the following steps (see the Code book for details, as well as the comments in the script itself):



The R script, `run_analysis.R`, does the following:

1. Download the dataset if it does not already exist in the working directory
2. Reading the data
3. Merges the two datasets
4. Extracts only the measurements on the mean and standard deviation for each measurement.
5. Merges the two datasets
6. Uses descriptive activity names to name the activities in the data set.
7. Appropriately labels the data set with descriptive variable names.
8. Creates a second, independent tidy set with the average of each variable for each activity and each subject.

The end result is shown in the file `tidy_data.txt`.
