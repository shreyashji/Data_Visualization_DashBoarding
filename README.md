## Data_Visualization_DashBoarding
## 1.Personal Financial Health/Status Dashboard;
<img align='centre' src="https://github.com/shreyashji/Data_Visualization_DashBoarding/blob/master/Financial%20dashboard.JPG" width="500">

- with KPIS like Networth , income , savings & expense %
- Expense % ,Saving % with change in income MOM,Detailed Statement
- Expense BreakDown,savings breakdown
- Income vs expense with trend line
- How do i spent,How i Save
- Do i spend accrding to what i earn
- All records are dummy in xlsx file change according to your need XD
- file used : Finance Database.xlsx .
- power bi dashboard file for refrence: my_finance_dashboard.pbix.

##STEPS TO FOLLOW FOR PERSONALIZED FINANCIAL DASHBOARD
--https://www.youtube.com/watch?v=pqSoCa2NGj4
--credits: codebasics Youtube channel

###put all your data in excel file according to you just dont change the type of 1 row 
-you can add more type by inerting new row & also new coln of months
-you can add/edit components
-only this 3 values should be thee in 1st coln saving , income,expense dont add any new thing here
-once all done now follow below things in power bi

###transorm data in power querry editor
-use the excel workbook to add you financial database file
-just unpivot the colns
-change the type of cols which have date-month-year to date & which have income no. to fixed deciamal  
-take out year from date col & name that taken out coln to year 
-close & apply
-after close & apply in data pan where tabular columns are prsnt change date column type & format=daymmm yy

-if you add new cols ,values in monthly ,to get this new dta ain power bi dashboard just refesh the data in the field option chosse the excel file table name and righ click and chosse refresh data



