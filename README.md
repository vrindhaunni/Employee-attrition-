# Employee Attrition-Dashboard


## Attrition

A reduction in the workforce due to employees leaving the organization voluntarily (resignations, retirements) or involuntarily (layoffs, terminations).
 
Employee attrition can impact organizational stability, productivity, and continuity of operations.

Attrition rates are typically measured and monitored to understand the reasons behind the losses and to implement strategies to mitigate them. 




### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Clean the data and load it to power bi.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 7 : Visual filters (Slicers) were added for the fields named "Gender", "PriorEducation field" .
- Step 8 : The card visuals were added to the canvas, for showing the total employees, total attrition, attrition rate, average age, Active employees.

- Step 9 : The different types of charts were added to the report design area representing the attrition insights with respect to department,gender,workbalance,martial status. 

- Step 10 : The report was then published to Power BI Service.


# Snapshot of Dashboard (Power BI Service)

![image](https://github.com/user-attachments/assets/b90e4b52-52b8-404a-a819-c6b5eb8beb10)
![image](https://github.com/user-attachments/assets/12cc4fba-a2a9-4f72-981d-4d7c4cda5854)
![image](https://github.com/user-attachments/assets/4fec30b6-3425-4e0e-964f-323366dc0a6a)



# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### Total Number of Employees = 4410
           
### ATTRTION RATE
          Attrition Rate = sum('Attrition data'[Attrition Count])/sum('Attrition data'[EmployeeCount])

  
  ### ACTIVE EMPLOYEES
             Active employees = sum('Attrition data'[EmployeeCount])-sum('Attrition data'[Attrition Count])


 ### Performance rate by martial status
    
![image](https://github.com/user-attachments/assets/d7e2f01c-5885-413f-bacb-6bd02ac8c280)

The performance rate is more for married peoples

 
 ### Work life balance interms of gender
        
![image](https://github.com/user-attachments/assets/ba641fe4-7682-4e27-876b-afc5cfc43107)

The work life balance is more for male
         
### Job satisfaction
          
        
![image](https://github.com/user-attachments/assets/53082c14-b3f3-4a06-9df7-dcfea9781741)

The job satisfaction rate is more of sales executive


### Attrition 

![image](https://github.com/user-attachments/assets/3cde872a-171b-481c-a33a-d0df2637299a)

The attrition count is more in research and development department

![image](https://github.com/user-attachments/assets/da8a45fa-b9c5-46b9-af8d-ca1f5c1998e3)

Also employees that have to business travel frequently also tend to leave the company more.

![image](https://github.com/user-attachments/assets/2458ebc6-4f52-4d16-ba74-d85db5658f1b)

In terms of attrition count is more for the age 29.

### Some other insights

The Total employee count is 4410 and total attrition count is 711

270 females and 441 males left this company

The attrition rate is 16.12%(Total attrition count / total employee count in %)

The average age of employee who left the company is 36.92

The employees currently working in this company is 3699

Employees that having 1 or less than 1 year experience are leaving the company more.

The work life balance is more for male

The performance rate is more for married peoples

The job satisfaction rate is more of sales executive

For the department Research and development having more percent salary hike

The male employees(16%) have more attrition rate than female employees(15%)

The active employees are more in life science field

Employees that having 1 or less than 1 year experience are leaving the company more.

Employees that having marital status single

Employees that not having satisfactory work life balance ,job and environmental status

Also employees that have to business travel frequently also tend to leave the company more.

Employees that are working on job role research director is leaving the company more.

In terms of attrition count is more for the age 29.

The attrition count is more in research and development department

Employees with 11% to 13% salary hike are more leaving the company.
Maximum number of employees are dissatisfied with companies environment

The monthly income being provided is also largely affecting the attrition as mostly the sales and research departments are paid well and the else are been at lower place.


### Conclusion

Employees are mostly leaving the company for the imbalance on the work life balance, job satisfaction, travelling, over time and salary hike. 
To reduce the attrition rate need to do proper measures from the company side

