# Part A - EDA
1. Understand the columns in the dataset and their datatypes. Wherever required, change 
   the datatype to suitable one. 
   For instance, quantity column should be numbers, Unit price should be float, Invoice 
   Data should be date, likewise check the available datatype and change wherever 
   required. 
2. Find out the count and distinct count of each column. 
3. Find out if any of the column has null values or not, if yes, how to deal with them?
4. Calculate Revenue per month and show in a data frame and a visual of your choice Write 
   down the inference out of this. 
5. Calculate cumulative revenue for across all months and show in a visual. 
6. Calculate monthly percent change in growth rate and show in a visual. Note down the 
   inference. 
7. Extract and Plot the following:
a. Revenue by country
b. Total active customer(unique count of customer id) by country and month
c. Total orders by country and month
d. Total orderlines by country and month
e. Total SKU (distinct count of Stock code) by country and month
f. Monthly revenue (avg) per order
8. Find whether a customer is the new customer or not. A new customer would be figured 
   out based on their first date of purchase. Figure out new customer on monthly basis. 
9. Find total revenue per month for new and existing customer per month. Show it in a 
   visual
10. Calculate total revenue per month by day for new and existing customer – in same 
    graph. (You can use line graph)
11. Calculate monthly retention rate (using crosstab() function of pandas) and find out total 
    retained user on a monthly basis. 
 
# Part B – Customer Segmentation
1. Calculate recency by finding inactive days for each customer. And then apply K – means 
   clustering to figure out recency score against each customer 
2. Calculate frequency by finding total number of orders for each customer and then apply K –
   means clustering to figure out the frequency cluster for each customer. 
3. Do the same for monetary / revenue
4. Add RFM to find out total score. 
5. Put an overall score and then categorise customer among best, medium and worst 
   customer. 
