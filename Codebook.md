This codebook summarises the variables of the ```summary_df.csv``` dataset.
The dataset summarises the mean value for several measurements taken using accelerometers and gyroscopes. 

For the details about the design of the study, the definition of the measurement variables and the time windows of the measurements, please refer to the website:

<http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones>

In particular, a detail discussion about naming convention of the variables can be found in the file "features_info.txt" in this archive:

<https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip>

Among the 561 variables of the original datasets, only the measurements related to mean and standard deviation are considered in the study.


## Identifier variables
- ```subjectId``` (1-30): the id of the person in the sample from which the measurements were taken
- ```activityName``` ("WALKING","WALKING_UPSTAIRS","WALKING_DOWNSTAIRS","SITTING","STANDING","LAYING"): the activity carried out by the person during the measurement


## Measurement variables
The measurements from accelerometer and gyroscope related to mean and standard deviation. See this website for the details of the definition:

<http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones>

- ``` tBodyAcc-mean()-X ``` 
- ``` tBodyAcc-mean()-Y ``` 
- ``` tBodyAcc-mean()-Z ``` 
- ``` tBodyAcc-std()-X ``` 
- ``` tBodyAcc-std()-Y ``` 
- ``` tBodyAcc-std()-Z ``` 
- ``` tGravityAcc-mean()-X ``` 
- ``` tGravityAcc-mean()-Y ``` 
- ``` tGravityAcc-mean()-Z ``` 
- ``` tGravityAcc-std()-X ``` 
- ``` tGravityAcc-std()-Y ``` 
- ``` tGravityAcc-std()-Z ``` 
- ``` tBodyAccJerk-mean()-X ``` 
- ``` tBodyAccJerk-mean()-Y ``` 
- ``` tBodyAccJerk-mean()-Z ``` 
- ``` tBodyAccJerk-std()-X ``` 
- ``` tBodyAccJerk-std()-Y ``` 
- ``` tBodyAccJerk-std()-Z ``` 
- ``` tBodyGyro-mean()-X ``` 
- ``` tBodyGyro-mean()-Y ``` 
- ``` tBodyGyro-mean()-Z ``` 
- ``` tBodyGyro-std()-X ``` 
- ``` tBodyGyro-std()-Y ``` 
- ``` tBodyGyro-std()-Z ``` 
- ``` tBodyGyroJerk-mean()-X ``` 
- ``` tBodyGyroJerk-mean()-Y ``` 
- ``` tBodyGyroJerk-mean()-Z ``` 
- ``` tBodyGyroJerk-std()-X ``` 
- ``` tBodyGyroJerk-std()-Y ``` 
- ``` tBodyGyroJerk-std()-Z ``` 
- ``` tBodyAccMag-mean() ``` 
- ``` tBodyAccMag-std() ``` 
- ``` tGravityAccMag-mean() ``` 
- ``` tGravityAccMag-std() ``` 
- ``` tBodyAccJerkMag-mean() ``` 
- ``` tBodyAccJerkMag-std() ``` 
- ``` tBodyGyroMag-mean() ``` 
- ``` tBodyGyroMag-std() ``` 
- ``` tBodyGyroJerkMag-mean() ``` 
- ``` tBodyGyroJerkMag-std() ``` 
- ``` fBodyAcc-mean()-X ``` 
- ``` fBodyAcc-mean()-Y ``` 
- ``` fBodyAcc-mean()-Z ``` 
- ``` fBodyAcc-std()-X ``` 
- ``` fBodyAcc-std()-Y ``` 
- ``` fBodyAcc-std()-Z ``` 
- ``` fBodyAcc-meanFreq()-X ``` 
- ``` fBodyAcc-meanFreq()-Y ``` 
- ``` fBodyAcc-meanFreq()-Z ``` 
- ``` fBodyAccJerk-mean()-X ``` 
- ``` fBodyAccJerk-mean()-Y ``` 
- ``` fBodyAccJerk-mean()-Z ``` 
- ``` fBodyAccJerk-std()-X ``` 
- ``` fBodyAccJerk-std()-Y ``` 
- ``` fBodyAccJerk-std()-Z ``` 
- ``` fBodyAccJerk-meanFreq()-X ``` 
- ``` fBodyAccJerk-meanFreq()-Y ``` 
- ``` fBodyAccJerk-meanFreq()-Z ``` 
- ``` fBodyGyro-mean()-X ``` 
- ``` fBodyGyro-mean()-Y ``` 
- ``` fBodyGyro-mean()-Z ``` 
- ``` fBodyGyro-std()-X ``` 
- ``` fBodyGyro-std()-Y ``` 
- ``` fBodyGyro-std()-Z ``` 
- ``` fBodyGyro-meanFreq()-X ``` 
- ``` fBodyGyro-meanFreq()-Y ``` 
- ``` fBodyGyro-meanFreq()-Z ``` 
- ``` fBodyAccMag-mean() ``` 
- ``` fBodyAccMag-std() ``` 
- ``` fBodyAccMag-meanFreq() ``` 
- ``` fBodyBodyAccJerkMag-mean() ``` 
- ``` fBodyBodyAccJerkMag-std() ``` 
- ``` fBodyBodyAccJerkMag-meanFreq() ``` 
- ``` fBodyBodyGyroMag-mean() ``` 
- ``` fBodyBodyGyroMag-std() ``` 
- ``` fBodyBodyGyroMag-meanFreq() ``` 
- ``` fBodyBodyGyroJerkMag-mean() ``` 
- ``` fBodyBodyGyroJerkMag-std() ``` 
- ``` fBodyBodyGyroJerkMag-meanFreq() ``` 
- ``` angle(tBodyAccMean,gravity) ``` 
- ``` angle(tBodyAccJerkMean),gravityMean) ``` 
- ``` angle(tBodyGyroMean,gravityMean) ``` 
- ``` angle(tBodyGyroJerkMean,gravityMean) ``` 
- ``` angle(X,gravityMean) ``` 
- ``` angle(Y,gravityMean) ``` 
- ``` angle(Z,gravityMean) ``` 