#  Providing bottleneck insights for local restaurant .

### Dashboard Link : 

## Problem Statement

A local restaurant has 2 branches in two localtion. Based on their sales data they want to find  out if there are opportunitues for cost cutting or if their is any bottleneck in their staffing operation.

**The consumer of this project or Dashboard will be the local branch manager who doesn,t have good command over finance but has great exprience over hospitallity domain and can understand his own operation well.

### Steps followed 

- Step 1 : Load data into Power query , dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so we need to select "column profiling based on entire dataset".
- Step 4 : Created a dimension table for brands  to normalize data & merged brand_id to fact survey table .



           
- Step 8 :DAX measures created for comprehensive & robust analysis and to create necessary kpi's .
           
           -Female respondents = CALCULATE([Total respondents],dim_repondents[Gender]="Female").
           -Male respondents = CALCULATE([Total respondents],dim_repondents[Gender]="Male"). 
           -Respondents % = DIVIDE([Total respondents],CALCULATE([Total respondents],ALL('fact_survey_responses')))
           -Total respondents = COUNTROWS(fact_survey_responses)

## Dashboard
          
          
![Screenshot 2024-09-29 192316](https://github.com/user-attachments/assets/9dedcf08-c40a-414b-89ab-c269b88da8df)
![Screenshot 2024-09-29 192332](https://github.com/user-attachments/assets/4182ed21-4cb1-4a53-b67e-5bd2f539f82e)
![Screenshot 2024-09-29 192400](https://github.com/user-attachments/assets/56f10bd5-6f90-4bc6-bd55-c1d10407bc32)
 

