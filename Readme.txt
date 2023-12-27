In this project, I have prepared a sales analytics dashboard using Microsoft Excel (2010). I was provided with data on sales of a cloth selling enterprise - Vrinda Store. Vrinda Store made sales through different e-commerce platforms in India in the year 2022.


Project Objectives:
1. Create a unified chart to contrast sales and orders.
2. Identify the month with the most substantial sales and order figures.
3. Determine whether men or women made more purchases in the year 2022.
4. Enumerate the various order statuses observed in 2022.
5. Compile a list of the top 7 states that have the most significant impact on sales.
6. Explore the correlation between age and gender based on order quantities.
7. Identify the primary sales-contributing channel.
8. Pinpoint the highest-selling category.

____________________________________________________________________________________________
Preparation of the dashboard:
1- I have made a copy of "Vrinda Store Raw Data For Analysis.xlsx" file and named that copy as "Vrinda Store Data Analysis - processed & Analysis.xlsx" then i formatted the worksheet to organise the data properly.
2- I found there were some duplication of datatypes and values, like "men and women" was also written as "m and w" in some places, in quantities; sometimes 1 was written as one etc. So, I spotted all such differences using filters and converted them in same kind of data to avoid confusions.
3- I created two additional columns, Age Group and Month, to assign quantity of customers of different age to their relevant age group and creation of Month eased to associate all sales
data under a particular month category.
Function used to add data in those columns:
x = row number
A- Age group: F(x)=IF(Ex>=50,"Senior",IF(Ex>=30,"Adult",IF(Ex>=20,"Young","Teenager")))
B- Month:     F(x)==TEXT(Gx,"mmmm")
4- Analyzed which data to include in dashboard to provide a holistic approach and generate effective report.
5- Created Pivot tables and Pivot charts for that data in different worksheets, included all the charts in dashboard worksheet (VRINDA STORE - ANNUAL REPORT - 2022).
6- Create a copy of "Vrinda Store Data Analysis - processed & Analysis.xlsx" and renamed that copy as "Vrinda Store - Annual Report - 2022".
7- Now, In "Vrinda Store - Annual Report - 2022.xlsx" I set the dashboard worksheet as first in order and hid the raw data worksheet (vrinda store).
____________________________________________________________________________________________

Here are my insights regarding the sales data of given entity:

> March emerged as the peak month, recording 2,819 orders totaling Rs. 1,928,066.
> Women accounted for Rs. 13,562,773, constituting 64% of the total sales.
> Order statuses in 2022 were as follows: 2% refunded, 3% returned, 3% cancelled, and 92% delivered.
> The top 7 states, listed in descending order, were Maharashtra, Karnataka, Uttar Pradesh, Telangana, Tamil Nadu, Delhi, and Kerala.
> Across all age groups, female customers outnumbered male customers.
> Amazon led in sales, followed by Myntra and then Flipkart.
> Set came out as the highest-selling category.