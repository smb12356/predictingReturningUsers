# Overview: 

</pre>
<pre>
Contrubuter  : Sandeep Bansal
Languages: Python
Tools/IDE: Anaconda
-
Libraries: 
pandas
numpy 
sklearn
sklearn.model_selection
sklearn.metrics recall_score
sklearn.metrics classification_report
sklearn.metrics confusion_matrix
sklearn.tree DecisionTreeClassifier

https://www.kaggle.com/code/anriueno/telco-customer-data-analysis-prediction/data




</pre>
</pre></b>

# Business Objective & Motivation:

Determine most pure dimensions or features that influence whether a customer will register or churn. 

# Abstract and Introduction:

Churn prediction is one of the most common use cases of machine learning. Churn can be anything—employee churn from a company, customer churn from a mobile subscription, and so on. Predicting customer churn is important for an organization because acquiring new customers is easy, but retaining them is more difficult. Similarly, high employee churn can also affect a company, since it spends a huge sum of money on grooming talent. Also, organizations that have high retention rates benefit from consistent growth, which can also lead to high referrals from existing customers.

### Data Types and Features
<p align="center">
  <img width="460" height="400"src="https://github.com/smb12356/predictingReturningUsers/blob/main/images/Screen%20Shot%202022-12-18%20at%2011.31.07%20AM.png?raw=true">
</p>


<p align="center">
  <img width="660" height="400" src="https://github.com/smb12356/predictingReturningUsers/blob/main/images/monthly%20Charges.png?raw=true">
</p>


<p align="center">
  <img width="860" height="500" src="https://github.com/smb12356/predictingReturningUsers/blob/main/images/Screen%20Shot%202022-12-04%20at%201.54.00%20PM.png?raw=true">
</p>

<p align="center">
  <img width="860" height="500" src="https://github.com/smb12356/predictingReturningUsers/blob/main/images/Screen%20Shot%202022-12-04%20at%201.53.01%20PM.png?raw=true">
</p>

  
# Proposed Methodology of Modeling:
### Decision Tree
According to sklearn documentation a Decision Tree is a non-parametric supervised learning method used for classification and regression. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features. A tree can be seen as a piecewise constant approximation.



### Random Forrest
“Random forests are based on the idea of creating an ensemble, which is where multiple models are combined together to produce a single prediction." To overcome the issue of overfitting, instead of training a single tree to find patterns in data, many trees are trained over random subsets of the data. The predictions of these trees are then averaged to produce a prediction. Combining trees together in this way is called a random forest. This technique has been found to overcome many of the weaknesses of regression trees.



# Results and Primary Findings:

![GitHub Logo](https://github.com/smb12356/predictingReturningUsers/blob/83fd711837eafe7ccc8de81610715c96c1742a61/images/married+male_female.png)


![GitHub Logo](https://github.com/smb12356/predictingReturningUsers/blob/83fd711837eafe7ccc8de81610715c96c1742a61/images/predictors%20with%20churb.png)




<p align="center">
  <img width="560" height="500" src="https://github.com/smb12356/predictingReturningUsers/blob/main/images/decisionTree.png?raw=true">
</p>





# Limitations and Future work:

Limitations in this project mostly surround the data itself. In any churn prediction analysis it's important to keep in mind that the objective is to predict whether a user will return or churn. Therefore it's important to obtain as much information about users as possible. Along with the data we have other characteristics that could be of use include:
- Location of each user
- How often user uses service.
- What days do they use service most.
- What days do they use service least.
- Specific age of each user
- User funnel route to user service
- length user has utilized service



# Conclusion and summary:

# References and contributions:

1. https://www.youtube.com/watch?v=cFKcDHzRcrM
2. https://www.kaggle.com/code/anriueno/telco-customer-data-analysis-prediction/data
3. Tommy Blanchard, Debasish Behera and Pranshu Bhatnagar. “Data Science for Marketing Analytics.”
4. https://scikit-learn.org/stable/modules/tree.html


