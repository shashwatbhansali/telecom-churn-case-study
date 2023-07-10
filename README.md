Businesss Problem:
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this _dfly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business goal.

To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.
Understanding the Business Objective and the Data
The dataset contains customer-level information for a span of four consecutive months - June, July, August and September. The months are encoded as 6, 7, 8 and 9, respectively.

The business objective is to predict the churn in the last (i.e. the ninth) month using the data (features) from the first three months. To do this task well, understanding the typical customer behaviour during churn will be helpful.
Data understanding:
In these we will import some of the important libraries like numpy , pandas, matplotlib , seaborn etc. Then we will read the data and analyse it.
Data cleaning:
In these we will deal missing values drop some rows and columns which are useful for our analysis. Then we will do otliers treatment finding new features in it.
EDA :
Then we plot some plot with the help of the univariate and bivariate analysis and check the correlation between the variables.
then we do some feature scaling by train test split and then we build the model by PCA ,logistic regression with PCA , SVM(Support Vector Machine) With PCA , Hyper Parameter tuning for SVC , RandomForest & PCA.
Conclusion:
The telecom industry experiences an annual churn rate of 15-25%, making customer retention more important than customer acquisition due to the high cost of acquiring new customers. To manage High Value Customer Churn, we predicted customers likely to churn and identified factors influencing high churn.
A considerable drop in recharge, call usage, and data usage in the 8th month (Action Phase) was observed during exploratory analysis.
Important predictors affecting churn include 'arpu_7', 'max_rech_amt_6', 'std_og_t2m_mou_8', 'loc_og_t2m_mou_8', 'max_rech_data_8', 'last_day_rch_amt_8', 'total_data_rech_8', 'total_amt_8', 'roam_og_mou_8', 'loc_ic_t2m_mou_8'.
The average revenue per user in the 7th month plays a vital role in predicting churn.
Local and STD minutes of usage (incoming and outgoing) are the most influential features on customer churn.
The last day of recharge amount in the action phase and the maximum recharge for calling data in the 6th and 8th months should be focused on to prevent churn.
The last day of recharge, total recharge for data done, and the total amount spent on calls and data in the 8th month also play a crucial role in indicating churn.
Outgoing roaming calls made by clients in the 8th month also play a key role in predicting churn.
Strategies to prevent churn include improving network and customer satisfaction, providing customized plans, routine feedback calls, introducing attractive offers, and promotional offers.








