# GettingAndCleaningData

**DS Specialization**

The goal of this project is to prepare tidy data that can be used for later analysis. It contains 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called *CodeBook.md*. It is also included a *README.md* in the repo with the scripts. This repo explains how all of the scripts work and how they are connected.

The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

<http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones>

Here are the data for the project:

<https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip>

The R script called *run_analysis.R* does the following:

1.-Download the data from the url.

2.-Merges the training and the test sets to create one data set.

3.-Extracts only the measurements on the mean and standard deviation for each measurement.

4.-Uses descriptive activity names to name the activities in the data set

5.-Appropriately labels the data set with descriptive variable names.

6.-From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. Write this new data set into two separate files, one with the headers called "*by_activity_subject_header.txt*" and another with the data called "*by_activity_subject_data.txt*".
