# About my cervical cancer prediction project

I imported the proper libraries:
* pandas
* numpy
* seaborn
* matplotlib

Step 1 was to do some EDA after importing my CSV file into a dataframe, by checking the data types of my features. I saw that a lot of my features were of the wrong data type, and I wanted to change that to ensure a smoother process for data analysis. I first needed to get rid of my missing values before I could change data types.

Step 2 was to handle missing values. I tackled this issue by replacing all '?' with a NaN, so that I could visualize all my missing data based on that. I created a heatmap of my dataset based on how many NaNs each feature contained, and this showed me that 2 features were almost entirely missing. The best course of action was to drop them from my dataset, so that is what I did.

Step 3 was to complete what I started in my 1st step, which was to change all my data types to numeric so that I could properly calculate the statistics of the dataframe.

Step 4 was to use the describe() function to calculate the mean of each feature, which I then used to replace the NaNs of each feature. Now I had no missing values, and a complete dataset.

Step 5 was to create some visualizations to analyze the correlations between my features, and to analyze the distribution of those features as well. 

Step 6 was to separate my target feature from the rest of my dataframe, and then scale it to ensure my model would not be biased by any of the features. I also split my data into training and testing data.

Step 7 was to create and train an XGBoost Classifier on my datasets.

## Results: The XGBoost Classifier achieved a 96% accuracy on predicting cervical cancer in the training data, and achieved a 97% accuracy on predicting cervical cancer in the testing data.
