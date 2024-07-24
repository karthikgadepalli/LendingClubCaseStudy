**LENDING CLUB CASE STUDY**

**Objective** 

LENDING CLUB  is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.Company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The purpose of this case study is to identify the risky loan applicants using EDA

**Project Description:**

  You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

•	If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

•	If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The loan data given contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.


 When a person applies for a loan, there are two types of decisions that could be taken by the company:
 
        1.	Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
        
            •	Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
            
            •	Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
            
            •	Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

   2.	Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)     
        

**Introduction:**

  Data analysis of this case study categorised in following steps:
  
    •	Data cleaning
    
    •	Data Manipulation
    
    •	Univariate Analysis
    
    •	Segmented Univariate Analysis
    
    •	Bivariate/Multivariate Analysis
    
      

**Methods Used:**

    •	Exploratory Data Analysis(EDA)
    
    •	Data Visualization
    
**Technologies Used**

    •	Python - 3.11.7
	
	•	Anaconda - 2.5.2
    
    •	Pandas - 2.1.4
    
    •	Jupyter - 7.0.8
    
    •	NumPy - 1.26.4
    
    •	Matplotlib - 3.8.0
    
    •	Seaborn - 0.12.2

**Conclusions/Suggestions**

		1.	Grade G loans were riskier followed by F, E, D, C, B, A.
		2.	More than 50% of F5 sub-grade type loans were defaulted, followed by G3 sub-grade type.
		3.	Percentage of defaulters were highest in the category of 'small_business' purpose.
		4.	Percentage of defaulters were high in those who opted for 60 months loan term than 36 months loan term.
		5.	Even though majority of the loans taken and defaulted are highest in CA state, NE state defaulter percentage is highest with ~60%.
		6.	Charged-off loan percentage is increasing as the ‘rate of interest’ and ‘revolving credit utilization’ is increasing.
		7.	More than 50% of loans with below criteria are charged-off:
			•	Loan amount between 21k & 35k and Active credit lines between 27 & 36.
			•	Interest rates between 21% & 24% and Revolving credit utilization between 0% & 20%.
			•	Interest rates between 21% & 24% and Debt to income ratio between 0% & 6%.
			•	Annual income between 58k and 85k and Active credit lines between 36 & 44.



**Contributer**

  •	Karthik Gadepalli
  
  •	Radhika Madhana	



