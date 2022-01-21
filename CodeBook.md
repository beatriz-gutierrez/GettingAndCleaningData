# Getting and Cleaning Data - Code Book

**Data Science Specialization**

This codebook describes each variable and its units, the data, and any transformations or work that you performed to clean up the data.


There are two text files as result of the transformations done in the run_analysis.R script, which are the following:

- "*by_activity_subject_header.txt*": contains the header of the result file.
- "*by_activity_subject_data.txt*": contains the data from the train and test files, group by the activity and the subject.

The type of each variable is described as follows:

        Activity: chr
        Subject: int
        TimeDomainSignal.BodyAccelerometer.Mean.CoordX: num
        TimeDomainSignal.BodyAccelerometer.Mean.CoordY: num
        TimeDomainSignal.BodyAccelerometer.Mean.CoordZ: num
        TimeDomainSignal.BodyAccelerometer.StandardDeviation.CoordX: num
        TimeDomainSignal.BodyAccelerometer.StandardDeviation.CoordY: num
        TimeDomainSignal.BodyAccelerometer.StandardDeviation.CoordZ: num
        TimeDomainSignal.GravityAccelerometer.Mean.CoordX: num
        TimeDomainSignal.GravityAccelerometer.Mean.CoordY: num
        TimeDomainSignal.GravityAccelerometer.Mean.CoordZ: num
        TimeDomainSignal.GravityAccelerometer.StandardDeviation.CoordX: num
        TimeDomainSignal.GravityAccelerometer.StandardDeviation.CoordY: num
        TimeDomainSignal.GravityAccelerometer.StandardDeviation.CoordZ: num
        TimeDomainSignal.BodyAccelerometerJerk.Mean.CoordX: num
        TimeDomainSignal.BodyAccelerometerJerk.Mean.CoordY: num
        TimeDomainSignal.BodyAccelerometerJerk.Mean.CoordZ: num
        TimeDomainSignal.BodyAccelerometerJerk.StandardDeviation.CoordX: num
        TimeDomainSignal.BodyAccelerometerJerk.StandardDeviation.CoordY: num
        TimeDomainSignal.BodyAccelerometerJerk.StandardDeviation.CoordZ: num
        TimeDomainSignal.BodyGyroscope.Mean.CoordX: num
        TimeDomainSignal.BodyGyroscope.Mean.: num
        TimeDomainSignal.BodyGyroscope.Mean.CoordZ: num
        TimeDomainSignal.BodyGyroscope.StandardDeviation.CoordX: num
        TimeDomainSignal.BodyGyroscope.StandardDeviation.CoordY: num
        TimeDomainSignal.BodyGyroscope.StandardDeviation.CoordZ: num
        TimeDomainSignal.BodyGyroscopeJerk.Mean.CoordX: num
        TimeDomainSignal.BodyGyroscopeJerk.Mean.CoordY: num
        TimeDomainSignal.BodyGyroscopeJerk.Mean.CoordZ: num
        TimeDomainSignal.BodyGyroscopeJerk.StandardDeviation.CoordX: num
        TimeDomainSignal.BodyGyroscopeJerk.StandardDeviation.CoordY: num
        TimeDomainSignal.BodyGyroscopeJerk.StandardDeviation.CoordZ: num
        TimeDomainSignal.BodyAccelerometerMagnitude.Mean: num
        TimeDomainSignal.BodyAccelerometerMagnitude.StandardDeviation: num
        TimeDomainSignal.GravityAccelerometerMagnitude.Mean: num
        TimeDomainSignal.GravityAccelerometerMagnitude.StandardDeviation: num
        TimeDomainSignal.BodyAccelerometerJerkMagnitude.Mean: num
        TimeDomainSignal.BodyAccelerometerJerkMagnitude.StandardDeviation: num
        TimeDomainSignal.BodyGyroscopeMagnitude.Mean: num
        TimeDomainSignal.BodyGyroscopeMagnitude.StandardDeviation: num
        TimeDomainSignal.BodyGyroscopeJerkMagnitude.Mean: num
        TimeDomainSignal.BodyGyroscopeJerkMagnitude.StandardDeviation: num
        FrequencyDomainSignal.BodyAccelerometer.Mean.CoordX: num
        FrequencyDomainSignal.BodyAccelerometer.Mean.CoordY: num
        FrequencyDomainSignal.BodyAccelerometer.Mean.CoordZ: num
        FrequencyDomainSignal.BodyAccelerometer.StandardDeviation.CoordX: num
        FrequencyDomainSignal.BodyAccelerometer.StandardDeviation.CoordY: num
        FrequencyDomainSignal.BodyAccelerometer.StandardDeviation.CoordZ: num
        FrequencyDomainSignal.BodyAccelerometer.MeanFrequency.CoordX: num
        FrequencyDomainSignal.BodyAccelerometer.MeanFrequency.CoordY: num
        FrequencyDomainSignal.BodyAccelerometer.MeanFrequency.CoordZ: num
        FrequencyDomainSignal.BodyAccelerometerJerk.Mean.CoordX: num
        FrequencyDomainSignal.BodyAccelerometerJerk.Mean.CoordY: num
        FrequencyDomainSignal.BodyAccelerometerJerk.Mean.CoordZ: num
        FrequencyDomainSignal.BodyAccelerometerJerk.StandardDeviation.CoordX: num
        FrequencyDomainSignal.BodyAccelerometerJerk.StandardDeviation.CoordY: num
        FrequencyDomainSignal.BodyAccelerometerJerk.StandardDeviation.CoordZ: num
        FrequencyDomainSignal.BodyAccelerometerJerk.MeanFrequency.CoordX: num
        FrequencyDomainSignal.BodyAccelerometerJerk.MeanFrequency.CoordY: num
        FrequencyDomainSignal.BodyAccelerometerJerk.MeanFrequency.CoordZ: num
        FrequencyDomainSignal.BodyGyroscope.Mean.CoordX: num
        FrequencyDomainSignal.BodyGyroscope.Mean.CoordY: num
        FrequencyDomainSignal.BodyGyroscope.Mean.CoordZ: num
        FrequencyDomainSignal.BodyGyroscope.StandardDeviation.CoordX: num
        FrequencyDomainSignal.BodyGyroscope.StandardDeviation.CoordY: num
        FrequencyDomainSignal.BodyGyroscope.StandardDeviation.CoordZ: num
        FrequencyDomainSignal.BodyGyroscope.MeanFrequency.CoordX: num
        FrequencyDomainSignal.BodyGyroscope.MeanFrequency.CoordY: num
        FrequencyDomainSignal.BodyGyroscope.MeanFrequency.CoordZ: num
        FrequencyDomainSignal.BodyAccelerometerMagnitude.Mean: num
        FrequencyDomainSignal.BodyAccelerometerMagnitude.StandardDeviation: num
        FrequencyDomainSignal.BodyAccelerometerMagnitude.MeanFrequency: num
        FrequencyDomainSignal.BodyBodyAccelerometerJerkMagnitude.Mean: num
        FrequencyDomainSignal.BodyBodyAccelerometerJerkMagnitude.StandardDeviation: num
        FrequencyDomainSignal.BodyBodyAccelerometerJerkMagnitude.MeanFrequency: num
        FrequencyDomainSignal.BodyBodyGyroscopeMagnitude.Mean: num
        FrequencyDomainSignal.BodyBodyGyroscopeMagnitude.StandardDeviation: num
        FrequencyDomainSignal.BodyBodyGyroscopeMagnitude.MeanFrequency: num
        FrequencyDomainSignal.BodyBodyGyroscopeJerkMagnitude.Mean: num
        FrequencyDomainSignal.BodyBodyGyroscopeJerkMagnitude.StandardDeviation: num
        FrequencyDomainSignal.BodyBodyGyroscopeJerkMagnitude.MeanFrequency: num
        
The description of each variable is described as follows:

1. Activity data comes directly from the corresponding train and test files: "*train\\X_train.txt*" and "*test\\subject_test.txt*"
This data are stored using the descriptive activity names from the "*\\activity_labels.txt*" file. 
1. Subject data comes directly from the corresponding train and test files: "*\\train\\subject_train.txt*" and "*\\test\\subject_test.txt*"
1. The rest of the columns comes from the values of the mean and standard deviation of the train and test data stored in: "*\\train\\X_train.txt*" and "*\\test\\X_test.txt*"
and their column names are defined in the "*\\features.txt*" file. All this data has been grouped by activity and subject, and the average of each variable has been calculated as a result tidy data set.


This code book attempts to be a continuation of the code book of the raw data used in this project. For further information, please check their code book located in the getdata_projectfiles_UCI HAR Dataset.zip file in the [GettingAndCleaningData GitHub repository](https://github.com/beatriz-gutierrez/GettingAndCleaningData) or check them online in <https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip>

