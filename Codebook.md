# CodeBook Description
This document is a codebook that provides descriptions of the variables, the data, and all transformations and work that I performed to clean up the data.

## The Data Source

Source data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Description of the dataset from the source website: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

## Abstract:

Human Activity Recognition database built from the recordings of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors.
Each subject performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist.

## The Data sets:

The dataset includes the following files (The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data):

'README.txt'

'features_info.txt': Shows information about the variables used on the feature vector.

'features.txt': List of all features.

'activity_labels.txt': Links the class labels with their activity name.

'train/X_train.txt': Training set.

'train/y_train.txt': Training labels.

'test/X_test.txt': Test set.

'test/y_test.txt': Test labels.

## Variables Information:

For each record it is provided:

- "subjectID" : An identifier of the subject who carried out the experiment. 
- "activityID" : Its activity label.
- 66 Mean value and Standard deviation measurements of the following variables: 
  - tBodyAcc-XYZ : Triaxial estimated body acceleration (time)
  - tGravityAcc-XYZ : Triaxial acceleration from the accelerometer (total acceleration) (time)
  - tBodyAccJerk-XYZ : Triaxial estimated body acceleration Jerk (time)
  - tBodyGyro-XYZ : Triaxial Angular velocity from the gyroscope (time)
  - tBodyGyroJerk-XYZ : Triaxial Angular velocity from the gyroscope Jerk (time)
  - tBodyAccMag : Triaxial estimated body acceleration Mag (time)
  - tGravityAccMag : Triaxial acceleration from the accelerometer (total acceleration) mag (time)
  - tBodyAccJerkMag : Triaxial estimated body acceleration Jerk Mag (time)
  - tBodyGyroMag : Triaxial Angular velocity from the gyroscope Mag (time)
  - tBodyGyroJerkMag : Triaxial Angular velocity from the gyroscope Jerk Mag (time)
  - fBodyAcc-XYZ :  Triaxial estimated body acceleration (frequency)
  - fBodyAccJerk-XYZ : Triaxial estimated body acceleration Jerk (frequency)
  - fBodyGyro-XYZ : Triaxial Angular velocity from the gyroscope (frequency)
  - fBodyAccMag : Triaxial estimated body acceleration Mag (frequency)
  - fBodyAccJerkMag : Triaxial estimated body acceleration Jerk Mag (frequency)
  - fBodyGyroMag :  Triaxial Angular velocity from the gyroscope Mag (frequency)
  - fBodyGyroJerkMag :  Triaxial Angular velocity from the gyroscope Jerk Mag (frequency)
 
 
