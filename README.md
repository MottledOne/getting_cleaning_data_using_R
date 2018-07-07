# getting_cleaning_data_using_R
# Assignment

# Input

The data used on this script can be found here.
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
http://archive.ics.uci.edu/ml/machine-learning-databases/00240/


The data is on a folder called UCI HAR Dataset, we will only need the following files:

activity_labels.txt

features.txt

subject_test.txt

subject_train.txt

X_test.txt

X_train.txt

y_test.txt

y_train.txt


# Output

It creates a tidy.txt which contains the average of each variable for each activity and each subject.

# Before Working
The working directory should be the place where the dataset is stored.

# Variables

variables are just the calculatd means and standard deviations of these sets of data - one each for the X, Y dimensions:

tBodyAcc-X

tBodyAcc-Y

tBodyAcc-Z

tBodyGyro-X

tBodyGyro-Y

tBodyGyro-Z

Each of these has a mean and standard deviation version. Examples:

tBodyAcc-mean()-X: Mean of base body acceleration data in the X dimension

tBodyGyro-std()-Y: Standard deviation of base body gyroscope measurement in the Y dimension
