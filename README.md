gettingandcleaningproject
=========================

This repository will be used to share Course Project from getting and cleaning data 

run_analysis.R will perform the operations required in this order:

* First it will download the zip file into the working directory (a subdirectory call data)
* After it will unzip and load proper tables
* It will merge all sets into one data set.
* Take only the measurements of the mean and standart deviation.
* Name all activities using descriptive activity names.
* Label the rows with descriptive activity names.
* Creates a new tidy data with the average of each variable


The tidy data object has 4 variables:

* Subject: The participant of the experiment.
* Activity: The activity perform by the participant.
* Variable: The dimension of the measure for the participant.
* Mean: average mean across a participant.