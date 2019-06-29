# LoanPrediction
<h4>Problem Statement:</h4>
<p>Dream Housing Finance company deals in all home loans. 
They have presence across all urban, semi urban and rural areas. 
Customer first apply for home loan after that company validates the customer eligibility for loan.
Company wants to automate the loan eligibility process (real time) based on customer detail provided while 
filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, 
Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify 
the customers segments, those are eligible for loan amount so that they can specifically target these customers.</p>
# Data Set source :
<h6>Analyticsvidhya</h6>
<h5>Approach:</h5>
<ul>
<li>Exploratory analysis of data. Figure out which features are categorical and which are continuous.</li>
Do proper Analysis of Continuous features. After analysis we get the some continuous features are highly skewed, transform that
continuous features using different mathmetical function.
<li>Encode the categorical features using one hot encoder. Scale the continuous features using MinMax scaling methods so that all
the continuous features comes under one scaling system.
Do feature engineering to generate new features e.g EMI, loan_to_income_ratio etc.</li>
</ul>
#Model Building:
<h6>Create following classification Model</h6>
<ul>
<li>LogisticRegression and tune its hyper parameter.</li>
<li>RandomForest, Tune its hyper parameter</li>
<li>GaussianNB, use class prior for imbalance data</li>
<li>KNN, Tune its hyperParameter</li></ul>
#Accuracy Metrics:
<h6>ROC curve and auc score.</h6>
#Conclusion:
<p>Random forest is good because the error difference between the train and test data set is minimum</p>
