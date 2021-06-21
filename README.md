**PreRequisite:**
!pip install zipcodes   -- for installing Zipcodes library .
# Personal-Loan-Campaign
Following task were carried out
1.	Perform an Exploratory Data Analysis on the data.
2.	Illustrate the insights based on EDA
3.	Data Pre-processing
4.	Model building - Logistic Regression
5.	Model performance evaluation and improvement using optimal threshold using AUC ROC curve, using Precision Recall curve.
6.	Model building – Decision Tree.
7.	Model performance evaluation and improvement  using pre pruning and post pruning using method
8.	Actionable Insights & Recommendations.
9.	EDA of misclassified data and identifying any patterns in misclassification.

For detailed notebook click [here](https://github.com/yogitadarade/Personal-Loan-Campaign/blob/3a6f616c6807162cb2de6f05b5b0c2fc3eb3231e/personal-loan-logistic-regression-decision-tree.ipynb)

**Context**

Thera Bankis a US bank that has a growing customer base. The majority of these customers are liability customers (depositors) with varying sizes of deposits. The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, the management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors).
A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio.

As a Data scientist at Thera Bank have to build a model that will help the marketing department to identify the potential customers who have a higher probability of purchasing the loan.

**Motivation** : To understand Logistic regression and Decision tree and explore this algorthims using Sklearn, Statmodel, Roc-Auc Curve,Precision Curve,Sequential feature selection, hyperparamter tuning Decision tress and post pruning Decision trees


**Insights & Recommendation**

- Decision trees doesn't require to much data preparation or handling of outliers like logistic regression. They are easy to understand. Decision tress can easily overfit , so we have to be careful using decision tree.
- Based on EDA, logistic Regression , Decision tree , Income ,Educatoin,Family,CCavg are most  important factor.
- Customers who have income above 98k dollars , Advance/graduate level education, a family of more than 2, such customers have higher chances of taking personal loans.
- So for this campaign we can have different profiles for customers.
- `High Profile Clients` :-Higher income,Advanced/Graduate level education, 3 /4 Family members,high spending
- `Average Profile` :- Medium income  group,Graduate level education.3/4Family members,medium spending
- `Low Profile`:-Lower income group,undergrads ,3/4Family Member,low spending
-  Customer Average Spending and Mortages can also be looked upon as based on EDA and logistic Regression this parameters also play some role in likelihood of buy loan.
- We can 1st  target high profile customers , by providing them with a personal relationship managers who can address there concerns and  can pursue them to buy loan from the   bank with completive interest rates.
- Prequalifying for Loan can also attract more customers.
- Our 2nd target would be Medium profile customers. 
- The model cannot identify  well if there are some exceptional cases when low profile customer is ready to buy a personal  loan.

