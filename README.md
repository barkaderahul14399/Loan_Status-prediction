Problem Statement: 

A Company wants to automate the loan eligibility process based on customer details provided while filling online application form. The details filled by the customer are Gender, Marital Status, Education, Number of Dependents, Income of self and co applicant, Required Loan Amount, Required Loan Term, Credit History and others. The requirements are as follows:                                                                                           

1.)Check eligibility of the Customer given the inputs described above.(Classification)

2.)Identify customer segments from given data and categorize customer into one of the segments.(Clustering)

3.)If customer is not eligible for the input required amount and duration:

a.)what can be amount for the given duration.(Regression)

b.)if duration is less than equal to 20 years, is customer eligible for required amount for some longer duration? What is that duration?(Regression)


             **Solution Steps------>
             
1)Classificatiom)

    1.Read Data
    
    2.Missing data Treatment
    
    3.Perform EDA
    
    4.Checking Correlations
    
    5.Standardize & One Hot Encoding Data
    
    6.Make Various models And Check their accuracy
    
    7.Tunning For Best value Of Parameters & Applying it on Models
    
    8.make prediction on Testing Data
    
2)Clustering
  
  1.Identify the Segment
  
  2.Standardize Segment
  
  3.make KMeans Clustering And checks Labels
  
  4.check value Of WCSS whithin the range to wich No of cluster will give better reasult
  
  5.Plot Elbow Curve(WCSS vs K)
  
  6.find Elbo point and make model on that no of clusters
  
  7.take input fro user Display Whole Cluster to Him/her


3)(A) Regression
   
   1.Separated all The Accepted And Rejected Loan Statuses in Two Datasets
   
   2.Declared Predict & Predictors
   
   3.Made AdaBoost model on Accepted Loans
   
   4.Rejected Loans Are Treated As Tesing Data
   
   5. Applied Accepted model Result on Rejected Data And Made Predictions



3)(B) Regression
   
   1.Separated Customers based on duration of Years(<20)taken Separately
   
   2.Separated all The Accepted And Rejected Loan Statuses in Two Datasets
   
   3.Declared Predict & Predictors
   
   4.Made AdaBoost model on Accepted Loans
   
   5.Rejected Loans Are Treated As Tesing Data
   
   6. Applied Accepted model Result on Rejected Data And Made Predictions
  
  
