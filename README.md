# Getting and Cleaning Data Course Project

## Description

Containes R script ```run_analysis.R``` that creates merges, tidy data set with 
the average of each variable for each activity and each subject from the 
'Human Activity Recognition Using Smartphones Data Set' 
avaliable at https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

## Tasks

Create one R script called run_analysis.R that does the following:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5.  From the data set in step 4, creates a second, independent tidy data set with the average 
    of each variable for each activity and each subject.

The code should have a file run_analysis.R in the main directory that can be run 
as long as the Samsung data is in your working directory. The output should be 
the tidy data set you submitted for part 1. You should include a README.md in 
the repo describing how the script works and the code book describing the 
variables.

## To work with script

* Download this data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
* Unpack the data in your working directory.
* Copy run_analysis.R to your working directory.
* Run ```source("run_analysis.R")```, then it will generate a new file tiny_data.txt in your working directory.

## Dependencies

```run_analysis.R``` depends on ```reshape2``` package. 
