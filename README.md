Problem Statement: 

A Company wants to automate the loan eligibility process based on customer details provided while filling online application form. The details filled by the customer are Gender, Marital Status, Education, Number of Dependents, Income of self and co applicant, Required Loan Amount, Required Loan Term, Credit History and others. The requirements are as follows:

1.)Check eligibility of the Customer given the inputs described above.(Classification)
2.)Identify customer segments from given data and categorize customer into one of the segments.(Clustering)
3.)If customer is not eligible for the input required amount and duration:
a.)what can be amount for the given duration.(Regression)
b.)if duration is less than equal to 20 years, is customer eligible for required amount for some longer duration? What is that duration?(Regression)

**Solution Steps:
1)Classificatiom)
Read Data
Missing data Treatment
Perform EDA
Checking Correlations
Standardize & One Hot Encoding Data
Make Various models And Check their accuracy 
Tunning For Best value Of Parameters
Applying it on Models 
make prediction on Testing Data
2)Clustering
Identify the Segment
Standardize Segment
make KMeans Clustering And checks Labels
ckeck value Of WCSS whithin the range to wich No of cluster will give better reasult
Plot Elbow Curve(WCSS vs K)
find Elbo point and make model on that no of clusters
take input fro user Display Whole Cluster to Him/her
