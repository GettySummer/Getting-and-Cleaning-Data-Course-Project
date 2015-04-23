---
title: "CodeBook"
author: "Summer Getty"
date: "Wednesday, April 22, 2015"
output: html_document
---

##Getting and Cleaning Data

###The script run_analysis.R performs these 5 steps:
  
1. Merges the training and the test sets to create one data set.

2. Extracts only the measurements on the mean and standard devation for each measurement.

3. Uses descriptive activity names to name the activities in the data set.

4. Appropriately labels the data set with descriptive variable names.

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Variables
* path_rf: file path
* files: the files
* dataActivityTest and dataSubjectTest and dataFeaturesTest: Test data from these files
* dataActivityTrain and dataSubjectTrain and dataFeaturesTrain: modified versions of these data sets.
* dataSubject and dataActivity and dataFeatures: combines the data sets.
* names(dataSubject) and names(dataActivity) and names(dataFeatures): sets the names for these data sets.
* dataCombine: combines data sets
* activityLabels: sets labels
* Data$activity: matches labels