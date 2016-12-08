How to get the data

1. Download from the given link and unzip it
2.Perform R script

Source data

the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

the data for the project: 

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

R script

a) download dataset
b) Unzip dataSet to /data directory
c) get the list of the files
d) read data from the files into the variables
e) read the Activity files
f) read the subject files
g) read the feature files
1. Merges the training and the test sets to create one data set
1.1 Concatenate the data tables by rows
1.2 set names to variables
1.3 Merge columns to get the data frame Data for all data
2. Extracts only the measurements on the mean and standard deviation for each measurement
2.1 Subset Name of Features by measurements on the mean and standard deviation
2.2 Subset the data frame Data by seleted names of Features
2.3 Check the structures of the data frame Data
3. Uses descriptive activity names to name the activities in the data set
3.1  Read descriptive activity names from “activity_labels.txt”
4. Appropriately labels the data set with descriptive variable names
5. Creates a second,independent tidy data set and ouput it
5.1 Making second tidy data set
5.2 Writing second tidy data set in txt file


variables:

x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.
features contains the correct names for the x_data dataset, which are applied to the column names stored in