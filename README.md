# Census-Income-Data-for-Adults-Used-car-sales
I used census income and used car sales datasets here to apply data engineering. For example, I removed outliers, split the data into training and test sets, created binary classifiers, built confusion matrix, and calculated the accuracy and made predictions.

CENSUS INCOME DATA FOR ADULTS
Some of the key features used in this work are: 
• Joined data frames
• Summarized the given data
• Split the data into training and validation set with a ratio of 70 and 30 for the training and validation dataset, respectively.
• Used the NaiveBayes classification algorithm and predicted the values
• Built the confusion matrix to understand the different features of dataset such as sensitivity, specificity, positive predictive value, negative predictive value

USED CAR SALES
Some of the key features used in this work are: 
• Dropped all the NA values to make the data set much more cleaner and converted the one of the columns into a binary factor column with two values of zero and one
• Visualized data using boxplots
• Calculated the mean and standard deviation
• Used pairs.panel, to show the distributions of each of the numeric features in the data set with outliers removed 
• For checking the normality of each column, I used two different methods one being the Kolmogorov-Smirnov test and another is the Shapiro-Wilk normality test.
• Performed normalization
• Checked correlations and visualized them using corrplot
• Split the data into training and validation set with a ratio of 75 and 25 for the training and validation dataset, respectively.
• Built three full multiple regression models for making predictions
• Used backward elimination procedure to eliminate the the worst or least trusted variable, one at a time
• Calculated R-squared value and RMSE values
• Used the log values to normalize the features
