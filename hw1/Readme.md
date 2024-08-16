Steps for performing the Dropout Prediction Challenge Kaggle competition
 
1. Merge data by student ID. The final merged data should have one row per unique student ID \\
2. Clean data and perform feature engineering. \\
3. Separate the data into training and test based on test IDs I have provided in testids.csv file. We will call the test dataset Kaggletest just to differentiate it from other test datasets we will create later in step 5. Set the kaggletest dataset aside until step 6. \\
4. Add the Dropout labels column to the train dataset by joining to the data in droppoutTrainlabels.csv file. \\
5. Fit various models to the training dataset by going through the usual process of further splitting this dataset into train and test and measuring performance. \\
6. Predict using the Kaggletest dataset. This will result in a column with 1s and 0s in the prediction object you create. \\
7. Combine this prediction column with the student ID column in the kaggletest dataframe and create a new data frame that has two columns Student ID and Dropout \\
8. Write the dataframe created above to a csv file and submit to Kaggle. Note: the submission file should look exactly like the sample submission file I have provided. Once you submit to Kaggle you will get the accuracy (F1 measure) that determines your position on the leaderboard. \\
 
Please see attached grading rubric for how you the project will be graded. Make sure you address everything in the grading rubric to get the best possible grade.
