
This is the course project required for the “Getting and Cleaning Data Course” offered from Coursera. A R programming script as (run_analysis.R ) has been developed to perform the tasks as expected in the course project. The detail function of the R script is as follows. 

1.	The data will be downloaded and copied in the working directory as initial requirement from the following source -  https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip .

2.	Loads the both datasets training and test from the source with the activity and feature information; 

3.	Only the mean and standard deviation columns will be considered in this analysis. The column names are standardized removing underscores and other characters; 

4.	Loads the activity and subject data for each dataset and merges those columns with both data sets;

5.	Converts the activity and subject columns into factors

6.	Finally, creates a tidy dataset as (tidy.txt) with mean and standard deviation value for each variable with the subject and activity.
