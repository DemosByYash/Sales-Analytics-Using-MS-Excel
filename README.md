# Sales-Analytics-using-MS-Excel
In this project, I have prepared a sales analytics dashboard using Microsoft Excel (2010). I was provided data of sales of a cloth selling enterprise - Vrinda Store. Vrinda Store made sales through different e-commerce platforms in India in the year 2022.

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

1-  
