The attached R script (run_analysis.R) performs the following to clean up the data:

Merges the training and test sets to create one data set, the result of which is a 10299x561 data frame

Reads features.txt and extracts only the measurements on the mean and standard deviation for each measurement. The result is a 10299x66 data frame

Reads activity_labels.txt and applies descriptive activity names to name the activities in the data set

The script also appropriately labels the data set with descriptive names: all feature names (attributes) and activity names are converted to lower case, underscores and brackets () are removed.

Finally, the script creates a 2nd, independent tidy data set with the average of each measurement for each activity and each subject. 
