Code book
============

###Steps for reading, merge and summarising UCI HAR Dataset:

1. Read test and train data frame with read.table function

2. Concate train and test data to one data frame with rbind function

3. Read test and train Y with read.table function

4. Concate train and test Y to one data frame with rbind function

5. Read test and train Subject with read.table function

6. Concate train and test Subject to one data frame with rbind function

7. Read Label with read.table function

8. Select columns, where finds "mean" or "std"

9. Merge data with name activiti

10. Use group_by func from dplyr for column "Action" and "Suject"
 
11. Summarise all columns with mean

####At the final we see tidy version of UCI HAR Dataset.  
