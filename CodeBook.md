# GettingAndCleaningData - CodeBook

**DS Specialization**

This codebook describes each variable and its units, the data, and any transformations or work that you performed to clean up the data.

There are tow text files as result of the transformations done in the run_analysis.R script, which are the following:
- by_activity_subject_header.txt
  Contains the header of the result file.
- by_activity_subject_data.txt
  Contains the data from the train and test files, group by the activity and the subject 
The columns are the following:
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
        FrequencyuencyDomainSignal.BodyAccelerometer.Mean.CoordX: num
        FrequencyuencyDomainSignal.BodyAccelerometer.Mean.CoordY: num
        FrequencyuencyDomainSignal.BodyAccelerometer.Mean.CoordZ: num
        FrequencyuencyDomainSignal.BodyAccelerometer.StandardDeviation.CoordX: num
        FrequencyuencyDomainSignal.BodyAccelerometer.StandardDeviation.CoordY: num
        FrequencyuencyDomainSignal.BodyAccelerometer.StandardDeviation.CoordZ: num
        FrequencyuencyDomainSignal.BodyAccelerometer.MeanFrequency.CoordX: num
        FrequencyuencyDomainSignal.BodyAccelerometer.MeanFrequency.CoordY: num
        FrequencyuencyDomainSignal.BodyAccelerometer.MeanFrequency.CoordZ: num
        FrequencyuencyDomainSignal.BodyAccelerometerJerk.Mean.CoordX: num
        FrequencyuencyDomainSignal.BodyAccelerometerJerk.Mean.CoordY: num
        FrequencyuencyDomainSignal.BodyAccelerometerJerk.Mean.CoordZ: num
        FrequencyuencyDomainSignal.BodyAccelerometerJerk.StandardDeviation.CoordX: num
        FrequencyuencyDomainSignal.BodyAccelerometerJerk.StandardDeviation.CoordY: num
        FrequencyuencyDomainSignal.BodyAccelerometerJerk.StandardDeviation.CoordZ: num
        FrequencyuencyDomainSignal.BodyAccelerometerJerk.MeanFrequency.CoordX: num
        FrequencyuencyDomainSignal.BodyAccelerometerJerk.MeanFrequency.CoordY: num
        FrequencyuencyDomainSignal.BodyAccelerometerJerk.MeanFrequency.CoordZ: num
        FrequencyuencyDomainSignal.BodyGyroscope.Mean.CoordX: num
        FrequencyuencyDomainSignal.BodyGyroscope.Mean.CoordY: num
        FrequencyuencyDomainSignal.BodyGyroscope.Mean.CoordZ: num
        FrequencyuencyDomainSignal.BodyGyroscope.StandardDeviation.CoordX: num
        FrequencyuencyDomainSignal.BodyGyroscope.StandardDeviation.CoordY: num
        FrequencyuencyDomainSignal.BodyGyroscope.StandardDeviation.CoordZ: num
        FrequencyuencyDomainSignal.BodyGyroscope.MeanFrequency.CoordX: num
        FrequencyuencyDomainSignal.BodyGyroscope.MeanFrequency.CoordY: num
        FrequencyuencyDomainSignal.BodyGyroscope.MeanFrequency.CoordZ: num
        FrequencyuencyDomainSignal.BodyAccelerometerMagnitude.Mean: num
        FrequencyuencyDomainSignal.BodyAccelerometerMagnitude.StandardDeviation: num
        FrequencyuencyDomainSignal.BodyAccelerometerMagnitude.MeanFrequency: num
        FrequencyuencyDomainSignal.BodyBodyAccelerometerJerkMagnitude.Mean: num
        FrequencyuencyDomainSignal.BodyBodyAccelerometerJerkMagnitude.StandardDeviation: num
        FrequencyuencyDomainSignal.BodyBodyAccelerometerJerkMagnitude.MeanFrequency: num
        FrequencyuencyDomainSignal.BodyBodyGyroscopeMagnitude.Mean: num
        FrequencyuencyDomainSignal.BodyBodyGyroscopeMagnitude.StandardDeviation: num
        FrequencyuencyDomainSignal.BodyBodyGyroscopeMagnitude.MeanFrequency: num
        FrequencyuencyDomainSignal.BodyBodyGyroscopeJerkMagnitude.Mean: num
        FrequencyuencyDomainSignal.BodyBodyGyroscopeJerkMagnitude.StandardDeviation: num
        FrequencyuencyDomainSignal.BodyBodyGyroscopeJerkMagnitude.MeanFrequency: num

For more details about these fields, please check the original data stored in the repository as getdata_projectfiles_UCI HAR Dataset.zip or check online in <https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip>

