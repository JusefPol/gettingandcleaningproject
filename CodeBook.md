### Description of the variables

* activity and feats: information related names of features and activity
* subject_test, X_test, Y_test: all info related to test
* subject_train, X_train, Y_train: all infor related to train.
* test and train_data: dataframes created with subject and y column added to rest of information.
* data: Merge of test and train_data
* mean_std_colnames: a vector with the name of all proper variables to extract (using grep to extract them.
* filterdata: is a data.frame with the columns we want
* melt_data: data melted using "melt" operation.
* tidy_data: final reshaped data.

Rest of information can be found in comments within the script, including references to the function patternReplace, found in stackoverflow.