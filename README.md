Activities are performed in the following order
R script called run_analysis.R that does the following: 1. Merges the training and the test sets to create one data set. 2. Extracts only the measurements on the mean and standard deviation for each measurement. 3. Uses descriptive activity names to name the activities in the data set 4. Appropriately labels the data set with descriptive activity names. 5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

It should run in a folder of the Samsung data (the zip had this folder: UCI HAR Dataset) The script assumes it has in it's working directory the following files and folders:

activity_labels.txt
features.txt
test/
train/
The output is created in working directory with the name of tidy2.txt

Note: the R script is built to run without including any libraries for the purpose of this course.

run_analysis.R walkthrough

It follows the goals step by step.

Step 1:
# 1. Merges the training and the test sets to create one data set.

# 2. Extracts only the measurements on the mean and standard deviation for each measurement. 

# 3. Uses descriptive activity names to name the activities in the data set

# 4. Appropriately labels the data set with descriptive activity names. 

# 5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
