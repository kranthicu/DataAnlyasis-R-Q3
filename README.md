First, unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".
Make sure the folder "data" and the run_analysis.R script are in current working directory.

Second, use source("run_analysis.R") command in RStudio.

Third, you will find two output files are generated in the current working directory:

data_merged.txt (7.9 Mb): it contains a data frame called cleanedData with 10299*68 dimension.

data_with_means.txt (220 Kb): it contains a data frame called result with 180*68 dimension.

Use data <- read.table("data_with_means.txt") command in RStudio to read the file. 

We can calculate the average of each variable for each activity and each subject. There are 6 activities, 30 subjects. There are  180 rows with all combinations for 66 features.
