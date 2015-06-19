# Getting_and_cleaning_data

This is a repository for the course project of the Coursera Getting and Cleaning Data course.

#Course Project

You should create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.

2. Extracts only the measurements on the mean and standard deviation for each measurement. 

3. Uses descriptive activity names to name the activities in the data set.

4. Appropriately labels the data set with descriptive variable names. 

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

#How it works

1. Download the data for the project (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) and put it into a folder on your local drive. The result is the folder: "UCI HAR Dataset".

2. Put run_analysis.R into this folder. 

3. Put the "UCI HAR Dataset" folder into your working directory (which can be found by running getwd() in RStudio), or set the location of the "UCI HAR Dataset" folder as your working directory using setwd() in RStudio.

4. Run source("run_analysis.R"), then it will generate a new file tidy_data.txt in your working directory.
