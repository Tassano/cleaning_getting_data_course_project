# cleaning_getting_data_course_project
## Repository to store and share the course project from the cleaning and getting data course on courser 


## Getting and Cleaning Data Course Project

## run_analysis.R script description

## The above mentioned script merges the Human Activity Recognition Using Smartphones Datasets   ## “train” and “test” to create a single dataset using the bind and rbind functions.

## Activities labels and patient numbers are also added as new columns to the merged dataset using bind.

## Also, the activities labels originally set as integers from 1 to 6 are replaced using the gsub function by their corresponding descriptive labels as follows:

#1-  WALKING
#2 - WALKING_UPSTAIRS
#3 - WALKING_DOWNSTAIRS
#4 - SITTING
#5 - STANDING
#6 - LAYING

#From the merged dataset named “data_11” a melted dataset called “new_data” is created using #the “melt function from the “Reshape2” package.

#The “new_data” dataset is casted using the cast function to create the “tidy_data” dataset #that contains the average of each variable for each activity and each subject.

#Finally a text file called "tidy_data_data_science_spec.txt”is created and saved in the #working directory. 

#IMPORTANT NOTE:The script requires that the package “reshapew2”  to run.



