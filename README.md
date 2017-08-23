# SamsungData
Samsung Data Repo for Getting and Cleaning Data Project Assignment


Analysis combining the Samsung trial and test data into a single, tidy set.
Before beginning the analysis, enter your filepath into the script.
Then the script can be run from any working directory.

First, the files are loaded into R.
Second, Variable names are taken from the features.txt file and moved onto the various data tables.
Third, the data frames for subject number, activity, and measurement values are
merged into a single data frame.
Fourth, values measuring the mean and standard deviation are extracted into a
new data frame.
Fifth, the indices for the various activities are replaced by their respective
names.
Sixth, other variable names throughout the data set are replaced so as to be 
more readable
Seventh, the data is aggregated into a tidy data set, tidyData, where all the
values are means of the respective measurements for a given subject number
and activity.
