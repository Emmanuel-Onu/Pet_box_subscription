# Pet_box_subscription
# Analyzing the impact of repeat purchases on sales

## Data Background   
PetMind is a retailer of products for pets. They are based in the United States. PetMind sells products that are a mix of luxury items and everyday items. Luxury items include toys. Everyday items include food. The company wants to increase sales by selling more everyday products repeatedly. They have been testing this approach for the last year. They now want a report on how repeat purchases impact sales  
&nbsp;  
![data table](https://github.com/Emmanuel-Onu/Pet_box_subscription/assets/106547277/5556510e-333a-4cad-b6b5-c8fd802ac638)  

&nbsp;    

## Task 1    
For every column in the data:    
a.	State whether the values match the description given in the table above.    
b.	State the number of missing values in the column.    
c.	Describe what you did to make values match the description if they did not match.    

## PRODUCT ID:  
There are 1500 unique values that match the description given. There are no missing values. No changes were made to this column.  
## CATEGORY: 
There were 7 unique values which are not consistent with the description given. There are 25 missing values. The missing values were replaced with Unknown as per the data description.
## ANIMAL:
There are 4 unique values that match the description given. There are no missing values. No changes were made to this column.
## SIZE:   
There are spelling inconsistencies. There are 3 unique values which are consistent with the description given. There are no missing values. The spelling inconsistencies were corrected by capitalizing each word. 
## PRICE:  
Values of this column are text data type. Not all values of this column are rounded to 2 decimal places which is inconsistent with the description. There are 150 missing values. The missing values were replaced with the overall median price which was 28.00. Values in this column were rounded to 2 decimal places. Values data types were formatted to fixed decimal numbers.
## SALES:  
Values of this column are positive, rounded to 2 decimal places as described. There are no missing values. No changes were made to this column.
## RATING:  
Values of this column ranged between 1 and 10 which is consistent with the description given. There are 150 missing values. Missing values were replaced with 0.
## REPEAT_PURCHASE:  
Values in this column ranged between 0 and 1. There are no missing values. No changes were made to this column.

## TASK 2  
Create a visualization that shows how many products are repeat purchases. Use the visualization to:  
     a. State which category of the variable repeat purchases has the most
         observations  
     b. Explain whether the observations are balanced across categories of the
          variable repeat purchases   
&nbsp;
There are 906 products which are repeat purchases. The category with the most observations is 1. The categories are unbalanced, with most observations being 1 which indicates a repeat purchase.  
&nbsp;  

![Repeat_Purchases](https://github.com/Emmanuel-Onu/Pet_box_subscription/assets/106547277/6fde5ddc-9726-473a-ace4-3a8de37c9b5d)

&nbsp;


## Task 3 
Describe the distribution of all of the sales. Your answer must include a visualization that shows the distribution.   
&nbsp;  
Considering the importance of sales to the marketing team, we should look at how sales are distributed.  
&nbsp;  
Looking at the graphic below, we can see that the sales distribution is unimodal and symmetric. There are some outliers that made more than 2000 in sales.  

&nbsp;

![Sales_Distribution](https://github.com/Emmanuel-Onu/Pet_box_subscription/assets/106547277/5c12924f-5963-4f64-afd7-729a01708ec6)
&nbsp;

## Task 4   
Describe the relationship between repeat purchases and sales. Your answer must include a visualization to demonstrate the relationship.  
&nbsp;  
The graphic below shows the relationship between sales and repeat purchases across categories. The relationship has a weak positive correlation.  
&nbsp;  
![Sales_and_Repeat_Purchases](https://github.com/Emmanuel-Onu/Pet_box_subscription/assets/106547277/981c7c9a-21ea-4699-a776-6cacea29c55c)

