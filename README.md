# Churn-Score
Churn rate is a marketing metric that describes the number of customers who leave a business over a specific time period.
Every user is assigned a prediction value that estimates their state of churn at any given time. This value is based on: User demographic information Browsing behavior Historical purchase data among other information It factors in our unique and proprietary predictions of how long a user will remain a customer. This score is updated every day for all users who have a minimum of one conversion. The values assigned are between 1 and 5.

**Task**
Your task is to predict the churn score for a website based on the features provided in the dataset.

**To Dos:**

1 .Firstly, load your Train Data in your local machine. 
2. Preprocess your data (Scaling, Categorical to numerical conversion, etc.) 
3. Split your data into two sets train_test_split(split_size = 0.7) 
4. Train your model train_set (Use 5-Fold cross validation to validate your model performance). 
5. Make predictions on test_set and get a score equal to or above 75%. 
You can use any models
