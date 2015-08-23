A code book to describe the newset.txt data file

This file shows the average value of mean and standard deviation of 86 variables for each subject and each activity.
They are calculated (taking average) from several meansurements for each subject and each subject, originally.

This is a 180*88 file.

The first and second colume shows the subject number and the activity name, respectively. 
There are 30 subjects who took the records and there are six activity names called:

1 WALKING
2 WALKING_UPSTAIRS
3 WALKING_DOWNSTAIR
4 SITTING
5 STANDING
6 LAYING

The remaining variable are the mean value mean() and stand deviation value std() of 
tBodyAcc-XYZ 
tGravityAcc-XYZ
tBodyAccJerk-XYZ
tBodyGyro-XYZ
tBodyGyroJerk-XYZ
tBodyAccMag
tGravityAccMag
tBodyAccJerkMag
tBodyGyroMag
tBodyGyroJerkMag
fBodyAcc-XYZ
fBodyAccJerk-XYZ
fBodyGyro-XYZ
fBodyAccMag
fBodyAccJerkMag
fBodyGyroMag
fBodyGyroJerkMag
angle(gravityMean)
angle(tBodyAccMean)
angle(tBodyAccJerkMean)
angle(tBodyGyroMean)
angle(tBodyGyroJerkMean)
and so on. 

in which XYZ means there exists 3 varibles for 3 directions

To be exact, they are the mean and std type value in the complete list in feature.txt in the next folder. Please refer to it for more infomation.
