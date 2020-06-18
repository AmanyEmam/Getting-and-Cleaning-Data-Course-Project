Peer-graded Assignment: Getting and Cleaning Data Course Project

First, download and unzip the data file into your R working directory.

Second, download the R source code into your R working directory.

Finally, execute R source code to generate tidy data file.

## Dataset

Human Activity Recognition Using Smartphones
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

## Files

* CodeBook.md which is a code book that describes all the variables, transformations that were performed to clean up the data ,and the final data

* run_analysis.R is an Rtrunscipt that includes all the data preparation and the coding in these following five steps:

** The first step: Merged the training and the test sets to create one data set.

** second step: Extracted only the measurements on the mean and standard deviation for each measurement.

** Third step: Used descriptive activity names to name the activities in the data set

** Fourth step: Appropriately labelled the data set with descriptive variable names.

** Last step: From the data set in step 4, created a second, independent tidy data set with the average of each variable for each activity and each subject.

* FinalData.txt is the exported final data after going through all the sequences described above.
