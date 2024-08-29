# Vrinda_Store_Data_Analysis_Using_Excel

Objective:- Vrinda Store wants to create an annual sales report for 2022 such that, Vrinda store can understand their customers and grow more sales in 2023.


Sample Questions:-
1. Compare the sales and orders using single chart
2. Which months got the highest sales and orders?
3. Who purchased more- Men or Women in 2022?
4. What are different order status in 2022?
5. List top 5 states contributing to the sales?
6. Relation between age and gender based on number of sales
7. Which channel is contributing to maximum sales?
8. Highest selling category?


Steps:-
Data cleaning:- In this step, we checked for inconsistencies, null values and dupliactes. And we found that the data was inconsistent, so we fixed it.

Data preprocessing:- Here, we created two extra columns. First, we created a column named 'Age Group' and the condition for this column was " if age>=50 then the age group value is senior,  if 50>age>=30 then the age group value is Adult , else age group value is Teenager ". Next, we created 'Month' column and we extracted month from 'Date' column.

Data analysis:- We used statistical tools and visualization techniques to understand the underlying patterns, relationships, and trends in the data.

Building interactive dashboard:- We combined all the charts in a single sheet and then added 3 slicers (slicer_1 : Month, slicer_2 : Channel, slicer_3: Category)

Insights:-
1. March month has the highest sales.
2. Women purchased more in 2022 i.e., women are more likely to buy compared to men (~65%)
3. The different order status are Delivered-92%, Refunded-2%, Returned-3%, Cancelled-3%
4. The top 5 states contributing to sales are Maharashtra, Karnataka, Uttar Pradesh, Telangana, Tamil Nadu.
5. The relation between age and gender based on number of orders is that adult age group(30-49 years) has maximum contribution (~50%)
6. Amazon, Flipkart and Myntra channels had maximum contribution (~80%)
   
Next steps/conclusion to improve Vrinda store sales:-
Target women customers of age group (30-49 years) living in Maharashtra, Karnataka, and UP by showing ads/offers/coupons available on Amazon, Flipkart and Myntra.
