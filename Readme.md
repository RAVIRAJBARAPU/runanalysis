The brief algorithm of code follows this sequence
## Dont bother about setwd, for my convenience to store the completed file i have selected this.
Store the file name if it was downloaded from the source website.
If no file exists with the specified file name, go to thew URL "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip "
and down load the zip file.
STEP 1: 
Download the file with the URL stored in (fileURL) with the file name stored in the variable (filename)
STEP 2: 
We have several txt files in the zip file (activity_labels,features,features_info)
read the data from text file activity_labels & store it in to the variable "activity".
Make second column in to characters (This is working out for future purpose).
read the data from text file features & store it in to the variable "features".
STEP 3:
Load Training & Test set data.
STEP 4:
Merge both the tests.

Finally write the Tidy data in to the test file Tidy.txt
