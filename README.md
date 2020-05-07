# Portfolio
This is a summary of all other repositories. For more details, please see: https://github.com/mays1770/Directory/blob/master/MayShao_Portfolio.pdf

## Marketing Analytics
### Recommender System
#### https://github.com/mays1770/RecommenderSystem
This project is to design personalized promotions to offer customers for a leading supermarket chain of over 400 stores. The full personalized promotion includes details about: all customers that will be targeted by the campaign, the soft drink product being offered, and the discount price assigned to each customer. We also generated an estimate of the total discount redemption cost along with the incremental volume as a result of our campaign.

### Pricing
#### https://github.com/mays1770/Pricing
This project is to develop a pricing scheme for the same superstore in last project. We set a pricing strategy that will maximize store revenues while still maintaining profits. There are a set of constraints that we must abide by. These constraints include 100 products that are to be priced, belonging to 2 product categories, to be offered at 10 stores. We find the combination of products, categories, and stores that optimize total revenue based on the new prices we set.

## Data Mining
### Spam_Email_Detection
#### https://github.com/mays1770/Spam_Email_Detection
The dataset can be found at http://archive.ics.uci.edu/ml/datasets/Spambase 
I used common machine learning algorithms such as lightGBM, SVM and tried stacking to classify spam vs. non-spam emails. The evaluation is based on overall accuracy and cost analysis. I also considered precision, recall, f1-score, ROC curves and other metrics in deciding the final model. The overall accuracy reaches 0.96.

### Bank_Deposit_Campaign
#### https://github.com/mays1770/Bank_Deposit_Campaign
A Portuguese bank has made marketing campaigns in order to sell deposits. Our goal is to utilize the data in order to predict whether or not a specific client will subscribe to a term deposit. We compared the performance of kNN, Decision Tree and Logistic Regression in this classification problem. We choose decision tree as our final model based on its overall accuracy (0.741) and business insights it can generate.

### Titanic with PySpark
#### https://github.com/mays1770/Titanic_PySpark
The dataset can be found at: https://www.kaggle.com/c/titanic/data The goal is to predict for each passenger whether he/she survived the Titanic tragedy by using the pipeline and feature functionality of pyspark.ml.In the pipeline, I assembled the following elements: StringIndexer, OneHotEncoder, VectorAssembler, LinearRegression. The AUC achieves 0.86.

### Ad Click-trough-rate Prediction
#### https://github.com/mays1770/OnlineAd_Click-Through-Rate_Prediction
This project involves predicting clicks for on-line advertisements. The training data consists of data for 9 days from October 21, 2014 to October 29, 2014. Our goal is to predict the probability of a click. The performance criterion used to evaluate the performance of prediction is log-loss. I used hashing and principal component analysis in data processing and adopted ensemble methods based on linear regression. The log-loss reaches 0.40.



