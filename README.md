## Getting and Cleaning Data
  This Repository contain the file results for the project of the Coursera course: Getting and Cleaning Data
by Jeff Leek, Roger D. Peng and Brian Caffo.

### Project Definition.

  
  The definition of the Project was:

  The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 
  
  The requirements was to submit: 1) a tidy data, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called **CodeBook.md**. You should also include a **README.md** in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.
  
  The main file is an R script called **run_analysis.R** that does the following: 
  - Merges the training and the test sets to create one data set.
  - Extracts only the measurements on the mean and standard deviation for each measurement. 
  - Uses descriptive activity names to name the activities in the data set
  - Appropriately labels the data set with descriptive activity names. 
  - Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
  
###run_analysis.R

1. Set the working directory to the UCI HAR Dataset parent directory.
2. Copy run_analysis.R into UCI HAR Dataset parent directory.
3. Run source("run_analysis.R")



   
   