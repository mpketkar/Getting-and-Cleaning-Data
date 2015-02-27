Codebook
========

Steps taken
----------------
#If required install the packages; "data.table" and "reshape2".#

if (!require("data.table")) {
  install.packages("data.table")
}

if (!require("reshape2")) {
  install.packages("reshape2")
}

require("data.table")
require("reshape2")

* Load: activity labels  
* Load: data column names  
* Extract only the measurements on the mean and standard deviation for each measurement.  
* Load and process X_test & y_test data.  
* Extract only the measurements on the mean and standard deviation for each measurement.  
* Load activity labels  
* Bind data  
* Load and process X_train & y_train data.  
* Extract only the measurements on the mean and standard deviation for each measurement.  
* Load activity data  
* Bind data  
* Merge test and train data  
* Apply mean function to dataset using dcast function  
* Write the tidy dataset.  

