Explanation about the script

The objective: create a new data set which somehow summarize the original data sets 

Firstly, we read all the related files. 
1 X-train, X-test:  the values of all variables.
2 y-train, y-test:  the activity number (1~6) 
3 subject-train, subject-test: the subject number (1~30)
4 activity_labels: connect the activity number to the descriptive name
5 feature: the descriptive names of variables

Secondly, merge the activity number and subject number and the values of all variables for train and test, respectively using function data.frame(x,y,z). Then merge the train set and test set to make a new one set using merge() function. By the way, here we first rename the column names of 561 variables with the names in feature.txt.

Thirdly, we pick up only the variables related with mean and standard deviation using the grep() function to the column names of new set.

Fouthly, we replace the subject number with the corresponding descriptive name.

Finally, we use the groupby function and summarize-each function in dplry package to calculate the average value of each variable for each subject and each activity. 

Write the final new set into a file called "newset.txt"




