# Patient Survival Analysis on Substance Abuse Data

Porject Description:  

Created a tool to help government officials and health professionals more effectively use their time and resources combating the negative effects of substance abuse in the United States. Goal is to accurately predict whether patients will complete their treatment as well as their length of stay. It is Regression and Classification problem. Submissions are judged based on accuracy and root mean squared error, respectively.  


Data:    

a. Prescriber data         
   > 1 million rows, 81 features       
   Includes zip code information as well as national provider identifiers (NPI)       
   Sufficient unique keys for merging to other data (demographic, crime, mapping)     
   
b. Treatment data       
   > 1.6 million rows, 70 features   
   Includes demographic and geographic information        
   Includes Patient’s current and past substance abuse issues.     
   
Target labels are Length of stay and Reason for leaving treatment.      

Exploratory Data Analysis:  

Data visualizations were developed in tableau software  to understand all the features. It played a crucial role in understanding the data well and how target variables are varying.

Machine Learning Model used:    

Light GBM is a gradient boosting framework that uses tree based learning algorithm.Light GBM grows tree vertically while other algorithm grows trees horizontally meaning that Light GBM grows tree leaf-wise while other algorithm grows level-wise. It will choose the leaf with max delta loss to grow. When growing the same leaf, Leaf-wise algorithm can reduce more loss than a level-wise algorithm.    

Results:

Our final model with effective Feature Engineering and Hyper Parameter tuning achieved a best accuracy of 74.2% and RMSE of 8.2 in the competition.
