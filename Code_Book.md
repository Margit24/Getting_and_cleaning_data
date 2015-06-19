#Code Book

This code book describes the variables, the data, and any transformations or work that was performed in order to clean up the data. 

#Original Data

- Original data source: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
- Description of original dataset: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

#Cleaning up the data
The attached R script (run_analysis_R) carries out the following actions in order to clean up the original data:

1. The script merges the training (X, Y and subject) and the test (X, Y and subject) sets to create one data set.

2. The script extracts only the measurements on the mean and standard deviation for each measurement from the features.txt file.

3. The script assigns descriptive names to the activities in the data set by reading activity_labels.txt (walking, walkingupstairs, walkingdownstairs, sitting, standing, laying)

4. The script appropriately labels the data set with descriptive activity names. Feature and activity names are converted to lower case and brackets and underscores are removed.

5. The script creates a second, independent tidy data set with the average of each variable for each activity and each subject. The result is saved as "tidy_data.txt". In this data set, the first column contains subject id's, the second column contains activity names and the other columns contain the averages for each of the 66 attributes. There are 30 subjects and 6 activities, which lead to 180 entries.


