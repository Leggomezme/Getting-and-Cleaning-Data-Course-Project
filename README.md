# About this R script "run_analysis.R"

 description of how the script works:

## 1.Merging the training and the test sets to create one data set.
### * Downloading and unzipping dataset
### * Reading files:
    *trainings tables
    *testing tables
    *feature vector
    *activity labels
### * Merging all data in one set

##  2.Extracting only the measurements on the mean and standard deviation for each measurement
* getting features indices which contain std and mean
## 3.Using descriptive activity names to name the activities in the data set
## 4.Appropriately labeling the data set with descriptive variable names
* getting names for variables
* updating colNames for new dataset
## 5.Creating a second, independent tidy data set with the average of each variable for each activity and each subject
* Making second tidy data set
* Writing second tidy data set in txt file
