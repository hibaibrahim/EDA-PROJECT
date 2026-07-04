# EDA-PROJECT
Title: Hotel Booking Insights Through EDA 
Problem Statment:  to analyze the data to understand the booking patters, cancellation patterns, also to 
check the revenue of the hotel and help the business to take better decisions
Objective: help to make the business understand the cancellation reasons and to visulaize the data
Total No.of Rows and columns: 119390, 32
Tools: python- numpy,pandas, matplotlib 
Insights: 1. dtypes function is used to check the data type and to see if the data present in the dataset is matching with 
             the datatypes mentioned
          2. isnull() function is to check the missing values present in the dataset and sum() function is used to add all the 
             missing values. if we dont use sum() then it will give us every single row having missing value
          3. dropna() function is used to drop the rows having null values. The total no of rows in the dataset  are 119390, 
             if i delete 488 rows from country and 4 rows from the children column it will not effect my analysis
          4. we are using fillna() function to fill the missing values with 0 in agents and company column.
             we are not dropping the missing values rows in agents and company column because it can be possible that the customer have 
             booked the room through hotel website without the need of agent or company
          5. here i am extracting the first 20 rows of the outliers and checking. i am not changing or dropping the outliers rows 
             because there can be a possiblity that the hotel room is luxury room or sit room or booked in peak season 
