# Getting and Cleaning Data Assignment

**Data Science Specialization**

### Purpose of the assignment

The goal of this assignment is to prepare tidy data that can be used for later analysis. 

It contains information about the raw data, the tidy data set, a link to a Github repository with the script for performing the analysis and the results and a code book that describes the variables, the data, and any transformations or work performed to clean up the data.


### The raw data

The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. Despite the fact that these data are tidy data, we consider them as raw data for our analysis. A full description is available at the site where the data was obtained:

<http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones>

Here are the data for the project:

<https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip>

Furthermore, this data is also available in the [GettingAndCleaningData GitHub repository](https://github.com/beatriz-gutierrez/GettingAndCleaningData) as a zip file called "*getdata_projectfiles_UCI HAR Dataset.zip*". The README.txt from this zip contains basic information about the content.


### The tidy data

The tidy data set is stored in the [GettingAndCleaningData GitHub repository](https://github.com/beatriz-gutierrez/GettingAndCleaningData) in two different files:

* The data is stored in the "*by_activity_subject_data.txt*" file.
* The header is stored in the "*by_activity_subject_header.txt*" file.
 

### The code book

The code book describes the variables, the data and any transformations or work that was performed to clean up the data and it is called "*CodeBook.md*". 


### The instruction list/script 

This section explains how the script works. The manipulation of the raw data to obtain the tidy data set is performed by R script called *run_analysis.R*, which is stored in the [GettingAndCleaningData GitHub repository](https://github.com/beatriz-gutierrez/GettingAndCleaningData).

This script does the following steps: 

        1.-Download the data from the url described above and unzip it.
        
        2.-Merges the training and the test sets to create one data set.
        
        3.-Extracts only the measurements on the mean and standard deviation for each measurement.
        
        4.-Uses descriptive activity names to name the activities in the data set.
        
        5.-Appropriately labels the data set with descriptive variable names.
        
        6.-From the data set in step 4, creates a second, independent tidy data set with the average of each variable
        for each activity and each subject. Write this new data set into two separate files, one with the headers 
        and another with the data.
