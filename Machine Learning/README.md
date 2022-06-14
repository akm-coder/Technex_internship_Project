# Telco Customer Churn Predication

<p>
It is important for every business to keep their customers happy. In order to increase their profit Margins they have to increase their customers by giving them best experience of product and the services. In this project we will be looking after the services that the customer has taken and his age and for how long the customer has been using their service and based on those parameters whether the customer is still using their services or has stopped using their services can be determined.
</p>

<p>
A telecommunications company is concerned about the number of customers leaving their land-line business for cable competitors. They need to understand who is leaving. Imagine that you are an analyst at this company and you have to find out who is leaving and why.
</p>

## About the dataset

We will use a telecommunications dataset for predicting customer churn. This is a historical customer dataset where each row represents one customer. The data is relatively easy to understand, and you may uncover insights you can use immediately. Typically it is less expensive to keep customers than acquire new ones, so the focus of this analysis is to predict the customers who will stay with the company.
This data set provides information to help you predict what behavior will help you to retain customers. You can analyze all relevant customer data and develop focused customer retention programs.

The dataset includes information about:
<ul>
<li> Customers who left within the last month – the column is called Churn</li>
<li> Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device    protection, tech support, and streaming TV and movies</li>
<li> Customer account information – how long they had been a customer, contract, payment method, paperless billing, monthly charges, and total charges</li>
<li> Demographic info about customers – gender, age range, and if they have partners and dependents</li>
</ul>

## Modeling (Logistic Regression with Scikit-learn)

<p>
We built our model using LogisticRegression from the Scikit-learn package. This function implements logistic regression and can use different numerical optimizers to find parameters, including ‘newton-cg’, ‘lbfgs’, ‘liblinear’, ‘sag’, ‘saga’ solvers. You can find extensive information about the pros and cons of these optimizers if you search it in the internet.
</p>

<p>
The version of Logistic Regression in Scikit-learn, support regularization. Regularization is a technique used to solve the overfitting problem of machine learning models. C parameter indicates inverse of regularization strength which must be a positive float. Smaller values specify stronger regularization.
 </p>

## Evaluation

For the evaluation of Logistic Regression, we used:
<ul>
<li> Jaccard index</li>
<li> Confusion matrix</li>
<li> Log loss</li>
</ul>
