# BCG-X-DATA-SCIENCE-VIRTUAL-INTERNSHIP

Welcome to the Data Science
We recognize that these tasks are challenging and that there are undoubtedly phrases and terminology you may not have heard before – don’t worry! We have tried to make this experience as true to life as possible and therefore our ask is that you attempt to seek out independent sources of information and do your own research, as required, to help guide you through the tasks.
 
Welcome to the Data Science program! BCG X is transforming the businesses of today through data science and advanced analytics initiatives and our goal is to help companies generate competitive advantage through these initiatives. This module is designed to give you a feel of what it is like to work at BCG X as we help our clients using data science.

Our client for this project is PowerCo, a major utilities company. PowerCo has had declining profits due to significant customer churn. We have been engaged to drive churn reduction within their Small & Medium Enterprise (SME) customers.

As a BCG X Data Scientist, you can expect to work in many different industries, and on many different types of business challenges. The skills you will use and develop today are part of the consultant and data scientist toolkits, and will be applicable to many different types of cases.
We hope you will enjoy your virtual experience and get a glimpse into the exciting life of a Data Scientist at BCG X!

# **Task-1: Business Understanding & Hypothesis Framing**

## **Background information of the task**

PowerCo is a major gas and electricity utility that supplies to corporate, SME (Small & Medium Enterprise), and residential customers. The power-liberalization of the energy market in Europe has led to significant customer churn, especially in the SME segment. They have partnered with BCG to help diagnose the source of churning SME customers.
A fair hypothesis is that price changes affect customer churn. Therefore, it is helpful to know which customers are more (or less) likely to churn at their current price, for which a good predictive model could be useful.
Moreover, for those customers that are at risk of churning, a discount might incentivize them to stay with our client. The head of the SME division is considering a 20% discount that is considered large enough to dissuade almost anyone from churning (especially those for whom price is the primary concern).
The Associate Director (AD) held an initial team meeting to discuss various hypotheses, including churn due to price sensitivity. After discussion with your team, you have been asked to go deeper on the hypothesis that the churn is driven by the customers’ price sensitivities. 
Your AD wants an email with your thoughts on how the team should go about testing this hypothesis. The client plans to use the predictive model on the 1st working day of every month to indicate to which customers the 20% discount should be offered.

## **Tasks:**
1. Understand what is going on with the client and to think about how you would approach this problem and test the specific hypothesis.
2. You must formulate the hypothesis as a data science problem and lay out the major steps needed to test this hypothesis.
3. Communicate your thoughts and findings in an email to your AD, focusing on the data that you would need from the client and the analytical models you would use to test such a hypothesis.

**If you are stuck:**
1. Remember what the key factors are for a customer deciding to stay with or switch providers
2. Think of data sources and fields that could be used to explore the contribution of various factors to a customer’s possible action 
3. Ideally, what would a data frame of your choice look like – what should each column and row represent? 
4. What kind of exploratory analyses on the relevant fields can give more insights about the customer's churn behavior? 


# **Task-2: EDA & Cleaning**

The BCG project team thinks that building a churn model to understand whether price sensitivity is the largest driver of churn has potential. The client has sent over some data and the AD wants you to perform some exploratory data analysis.

The data that was sent over includes:

1. Historical customer data: Customer data such as usage, sign up date, forecasted usage etc
2. Historical pricing data: variable and fixed pricing data etc
3. Churn indicator: whether each customer has churned or not

### **Sub-Task 1:**

Perform some exploratory data analysis. Look into the data types, data statistics, specific parameters, and variable distributions. This first subtask is for you to gain a holistic understanding of the dataset. You should spend around 1 hour on this.

### **Sub-Task 2:**

Verify the hypothesis of price sensitivity being to some extent correlated with churn. It is up to you to define price sensitivity and calculate it. You should spend around 30 minutes on this.

# **Task-3: BFeature Engineering & Modelling**




### **Sub-Task 3:**

### **Sub-Task 1**

Your colleague has done some work on engineering the features within the cleaned dataset and has calculated a feature which seems to have predictive power. 

This feature is “the difference between off-peak prices in December and January the preceding year”. 

Run the cells in the notebook provided (named feature_engineering.ipynb) to re-create this feature. then try to think of ways to improve the feature’s predictive power and elaborate why you made those choices. 

You should spend 1 - 1.5 hours on this. Be sure to make use of the “feature_engineering.ipynb” notebook to get started with re-creating your colleagues' features.

### **Sub-Task 2**

Now that you have a dataset of cleaned and engineered features, it is time to build a predictive model to see how well these features are able to predict a customer churning. It is your task to train a Random Forest classifier and to evaluate the results in an appropriate manner. We would also like you to document the advantages and disadvantages of using a Random Forest for this use case. It is up to you how to fulfill this task, but you may want to use the below points to guide your work:

* Ensure you’re able to explain the performance of your model, where did the model underperform?
* Why did you choose the evaluation metrics that you used? Please elaborate on your choices.
* Document the advantages and disadvantages of using the Random Forest for this use case.
* Do you think that the model performance is satisfactory? Give justification for your answer.
* (Bonus) - Relate the model performance to the client's financial performance with the introduction of the discount proposition. How much money could a client save with the use of the model? What assumptions did you make to come to this conclusion?
* You should spend 1 - 1.5 hours on this. When it comes to model evaluation and the explanation of your results, feel free to use the additional links below.

If you are stuck:

#### **Sub-Task 1**

1. Think of ways to evaluate a feature against a label.
2. Think of ways to add new features which would complement the already existing ones. 
3. Think of feature granularity. 
4. Remove unnecessary features.
 
#### **Sub-Task 2**

1. Is this problem best represented as classification or regression? 
2. What kind of model performance do you think is appropriate? 
3. Most importantly how would you measure such a performance? 
4. How would you tie business metrics such as profits or savings to the model performance?

# **Task 4: Executive Business Summary**

Prepare a half-page summary or slide of key findings and add some suggestions for data augmentation – which other sources of data should the client provide you with and which open source datasets might be useful? You should spend 10-15 minutes on this.

Develop an abstract slide synthesizing all the findings from the project so far, keeping in mind that this will be for the key stakeholders meeting which the Head of the SME division, as well as other various stakeholders, will be attending.

**Note:** a steering committee meeting is a meeting where the BCG team presents key findings and recommendations (and/or project progress) to key client stakeholders.

Please use the template below and submit your summary slide in PDF format. 

A few things to think about for this abstract include:

* What is the most important number or metric to share with the client?
* What impact would the model have on the client’s bottom line?

Please note, there are multiple ways to approach the task and that the sample answer is just one way to do it.
