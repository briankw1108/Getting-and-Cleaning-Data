Getting and Cleaning Data Project
=================================

run_analysis.R
---------------------------------
This cleanup script does the following:
1. Merge training and test data sets to be a new data set.
2. Extract the variables with "-mean()" and "-std()".
3. Label the names of activity with feature.txt.
4. Label all variable names.
5. Create a new data set with the means of each subject and activity.


Running the script of run_analysis.R(The steps below explains how the run_analysis.R runs)
---------------------------------
1. setup working directory to desktop.
2. create a folder on desktop if the folder is not existed.
3. file source address
4. download the file from the file source.
5. unzip the .zip data.
6. setup new working directory to new unzipped folder.
7. read the features file
8. merge train data set.
9. merge test data set.
10. merge train and test data set
11. get the indices from all measurements that contain mean and std#extract the measurements that contain mean and std
12. label activities
13. reshape the data set by melting the data
14. calculate means for all variables for each subject and activity by using dcast function
15. create a text file that contains this new data set with means for each subject and activity.


Final Result
---------------------------------
The final new data set is at https://github.com/briankw1108/Getting-and-Cleaning-Data/blob/master/Analysis_Cleaned_Data.txt


