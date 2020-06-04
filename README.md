# Getting and cleaning data week 4 project
Repo for Coursera's "Getting and Cleaning Data" week 4 project


## Files provided:
- "CodeBook.md" describes the variables and the data.
- "run_analysis.R" contains all the code to perform the analyses described in the 5 steps
- "tidyData.txt" is the output of the final step

# Libraries Required
dplyr

## How to get to the tinyData.txt:

Download data from the link below and unzip it into working directory of R Studio: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Execute the R script "run_analysis.R". They can be launched in RStudio by just importing the file. Here are the five steps:

1. Reading in the files and merging the training and the test sets to create one data set
  - Reads training and test datasets
  - Merges dataset into one set
2. Extracting only the measurements on the mean and sd for each measurement
  - Creates a vector based on features.text (variables labels)
  - Filters variables based on "mean" and "std" measurements
  - Subsets dataset based on filtered variables
3. Use descriptive activity names to name the activities in the data set
  - Merges selected variables and activity and subject columns 
  - Reads activity labels
  - Replaces activity codes by labels
4. Appropriately labels the data set with descriptive variable names
  - Using colnames
5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject
  - Makes a tidy data set, ordering columns by SubjectID and activityID
  - Writes a tidy data set into a txt file 
  
