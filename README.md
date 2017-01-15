# GettingAndCleaningData_FinalAssignment
This README describes the content of the repository. It contains the files to run the analysis for the final assignment of the Coursera.org course "Getting and cleaning data":

<https://www.coursera.org/learn/data-cleaning/home/welcome>

## Content of the repository
The repository contains the following files:
- ```run_analysis.R```: this is the script which performs the analysis (details are given below)
- ```Codebook.md```: this file contains the description of the variables used in the analysis
- ```summary_df.txt```: it's the output tidy dataset
- ``` README.md```: this file

## How to run the analysis
In order to run the analysis you need the **reshape2** package. If you don't have it, you can install it inside an R session with the following command:
```
install.packages("reshape2",dependencies = TRUE)
```

To reproduce the result of ```summary_df.txt``` one has to run the following command in an R session:
```
source('run_analysis.R')
```

## Description of the analysis
The analysis starts from downloading the datasets from the following website:

<http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones>

The measurements stored in the files refer to the data from accelerometers and gyroscopes embedded in smartphones worn by two groups of "train" and "test" people. 
More information is given at the website and inside the Codebook.md file.

The analysis proceeds as follows:

1. the script checks if the input dataset is present in the directory: if not it downloads and unzips it;

2. the ```features``` data.frame is created by reading the "features.txt" file (using read.table). This data.frame contains the on the (561) variables measured by the accelerometers and gyroscopes; 

3. the ```activities``` data.frame is created by reading the "activity_labels.txt" file;

4. for the "train" set, the "X_train.txt", the "y_train.txt" and the "subject_train.txt" files are read and imported as data.frames. For the ```X_train``` data.frame only the features related to mean and standard deviation are retained. The 3 data.frames are collapsed to one data.frame called ```train``` by using the cbind function;

5. the same operation as in 4 is repeated for the ```test``` dataset;

6. the ```train``` and ```test``` data.frame are merged using rbind into a single dataset called ```merged```;

7. the activity name is added to the ```merged``` data.frame using the merge function; 

8. a _molten_ (or _narrow_) data.frame (called ```molten```) is created from the merged data.frame using subjectId and activityName as id.vars; 

9. the final aggregation to create the output dataset (called ```out_df```) is done using the dcast function of the reshape2 package, specifying ```fun.aggregate = mean```.


