# Neural_Network Charity Analysis

## Overview
This project tried to predict whether applicants will be successful if funded by the Alphabet Soup Co. Alphabet Soup Co. wants to provide funding to companies but it needs to know in advance whether it will be successful or not.  


## Results
- **Data Processing**
   - To clean the data I removed the EIN and NAME columns since they have no value to the model. 
   - The varibales being considered for my model are as follows: 'STATUS', 'ASK_AMT', 'IS_SUCCESSFUL', 'APPLICATION_TYPE', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT'. I dropped "USE_CASE_Other","AFFILIATION_Other" columns. 
   - My Dependent varible is "IS_SUCCESFUL" since we want to try to predict this with high accuracy. 
   
  
  
  
 
  
## Summary 
On Average my models kept around 73% accuracy score which is decent considering it was an improvement. My recommendation to improve this model would be to find better features to help explain what determines "IS_SUCCESFUL" such as more indepth knowledge of the other associates/ firms being funded. At the end of the day, knowledge is power and if we had more indepth data between all these applications, we can create a better model.
