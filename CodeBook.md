# Code Book
"tidy.txt" is a tidy data det created from Human Activity Recognition Using Smartphones Dataset. To do so, "run_analysis.R" codes were employed into following files:
- 'features.txt': List of all features.

- 'activity_labels.txt': Links the class labels with their activity name.

- 'train/X_train.txt': Training set.

- 'train/y_train.txt': Training labels.

- 'test/X_test.txt': Test set.

- 'test/y_test.txt': Test labels.

- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 
 
## Variables in "run_analysis.R"
- subtest & subtrain: to read "subject_test" & "subject_train" data sets
- xtest & xtrain: to read "X_test" & "X_train" data sets
- ytest & ytrain: to read "y_test" & "y_train" data sets
- subdata: to read "subject_test" & "subject_train" data set
- features: to read "features" data set
- activity: to read "activity_labels" data set
