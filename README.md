#  Providing bottleneck insights for local restaurant .

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMDZlYWMyNzctZDg5OC00NjQ4LWEzZDEtNjE0ZDNiMzNkMjViIiwidCI6Ijg2OTY0MTdiLTM1NDgtNDFjNC04NTU3LWE0ZWRjN2U4NTQ4MSIsImMiOjEwfQ%3D%3D

## Problem Statement

A local restaurant has 2 branches in two localtion. Based on their POS and Timesheet data they want to find  out if there are opportunitues for cost cutting or if their is any bottleneck in their staffing operation.

**The consumer of this project or Dashboard will be the local branch manager who doesn,t have good command over finance but has great exprience over hospitallity domain and can understand his own operation well.

### Steps followed 

- Step 1 : Load data into Power query , dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : From timesheet table separated shift duration , total hours worked from shift   duration 
- Step 4 : From shift duration  segmented hours after 9 PM and hours before 8 AM to find insight about staffing operation.
- Step 4 : Created a separate date column .



           
- Step 8 :DAX measures created for comprehensive & robust analysis and to create necessary kpi's .
           
           - Avg shift per day
           - COGS 
           - Employee to sales ratio 
           - Employees
           - Gross Profit
           - Net Profit 
           - Net Revenue
           - Products
           - Shifts
           - #Orders
           - Total sales
           - Transactions

- Step 9 : Answering Business questions --
### Ad Hoc question 1 : Identify peak business hour or when do we receive most orders  ? Mainly identify based on location & weekdays .
![Screenshot 2024-10-13 202128](https://github.com/user-attachments/assets/59824b43-611c-4cd6-9f5f-3c6f71ffc2d4)

- Our peak business hour is (12 PM-6 PM) , more specifically (12 PM - 3 PM).
- Almost 67% of orders are placed between  (12 PM-6 PM) and overall  almost 47% of orders placed between (12 PM - 3 PM).
- We can see little anomaly in Chittagong precisely in early morning hour (6AM-9AM) ,where Chittagong is having more orders than Dhaka.


## Dashboard
          
          
![Screenshot 2024-09-29 192316](https://github.com/user-attachments/assets/9dedcf08-c40a-414b-89ab-c269b88da8df)
![Screenshot 2024-09-29 192332](https://github.com/user-attachments/assets/4182ed21-4cb1-4a53-b67e-5bd2f539f82e)
![Screenshot 2024-09-29 192400](https://github.com/user-attachments/assets/56f10bd5-6f90-4bc6-bd55-c1d10407bc32)
 

