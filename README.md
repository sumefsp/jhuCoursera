jhuCoursera
===========
## Getting and Cleaning Data
  For the working of the script [run_analysis.R](./run_analysis.R) please refer to [CodeBook.md](./CodeBook.md)
* [run_analysis.R](./run_analysis.R) - The script that cleans up the data and produces a tidy data that consists of only the mean of data of the mean measurements and standard deviation measurements of various datasets of the experiment performed by SmartLab on Wearable Computing.
* [README.txt](./README.txt) - The file consisting the details of the experimental data released by the researchers of SmartLab.
* [tidy.txt](./tidy.txt) - The raw file containing the tidy data produced from 'run_analysis.R' script.
* Directories [test](./test) and [train](./train) consist of the measured data for Test Set and Train Set respectively.
* [features_info.txt](./features_info.txt) - Shows information about the variables used on the feature vector.
* [features.txt](./features.txt) - List of all features.
* [activity_labels.txt](./activity_labels.txt) - Links the class labels with their activity name.

### Files Used in the cleaning up for the tidy data produced by 'run_analysis.R'
    All paths are relative to the current directory location in Linux path convention.
* [./test/subject_test.txt](./test/subject_test.txt)
* [./test/X_test.txt](./test/X_test.txt)
* [./test/y_test.txt](./test/y_test.txt)
* [./train/subject_train.txt](./train/subject_train.txt)
* [./train/X_train.txt](./train/X_train.txt)
* [./train/y_train.txt](./train/y_train.txt)
* [./activity_labels.txt](./activity_labels.txt)
* [./features.txt](./features.txt)