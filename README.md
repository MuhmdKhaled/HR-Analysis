HR Data Analytics Power BI Report
----------------------------------------------------------------------------------------------------------------------------------------

Project Description:
--------------------------------------------------------------------------------------------------------------------------------------
This Power BI report provides comprehensive analysis of the employees in a company.
I made this dashboard trying to help the stakeholder to make the right decisions relating to the employees.


How to Use:
------------------------------------------------------------------------------------------------------------------------------------------------------
Download the report file (HR project.pbix).

Open it using Power BI Desktop.

Explore the visualizations and charts to analyze employees data.

Interact with the charts to get the specific information you want.

you can also download the raw data if you want to show the data before processing from the data files ( HR Analytics Data.csv & HR employee data.csv)

Requirements:
---------------------------------------------------------------------------------------------------------------------------------------------------------
Power BI Desktop to open the report file (can be downloaded for free from the Power BI website).

Steps i followed in this report :

step 1 : I loaded the data into Power Query editor to transform the data to improve the quality of it. These tranformations are the followings:

(1) splitting the columns by delimiter (Tap delimiter).

(2)Changing data types of some columns.

(3) Promoted headers ( use first row as header).

(4) Add som conditional columns that help me getting the insights.

These Condiotional columns are >>

_ "Reach retirement age" if the employee's age is greater than or equal 60 then "Yes" and else "No".

_"Distance between company and home" >> if the Distance from home greater than or equal 20 then "Far" else if this distance is greater than or equal " Close" else "Very close".

_"Experience" >> if TotalWorkingYears is less than or equal 1 then "No expeience" else if the years is less than or equal 5 then "Mid experienced" else if the years is less than or equal 20 then "Highly experienced" else " Top experienced".

_ "Retrenchment " >> if YearsAtCompany is greater than or equal 18 then "Yes" else "No"

_"Promotion" >> if YearsSinceLastPromotion is greater thanor equal 10 the " Need to promotion" else then " No Need to promotion"

_ "Experience_level" >> if JobLevel = 1 then "Junior" else if = 2 then "Senior" else if then = 3 then "Team leader" else if = 4 then "Project manager" else then " Manager"

_"Performance" >> PerformanceRating = 3 then "Median" else then "High"

_"Statisfaction(Job)" >> if JobSatisfaction is less than or equal 2 then "Low" else if = 3 then "Median" else then "High"

(5) Inserting Merged columns and these columns are :

_"Level of job" which resulted from merging columns "JobLevel" with word "level"

_"Num of Ex companies" which resulted from merging columns "NumCompaniesWorked" with word "companies"

step 2 : apply these the transformations on the data and load the data

The dashboard I divided it into 6 pages and each page showing a specific information . I added a page navigator in all pages to move between the Pages easily " by Click on the page in the navigator with clicking ctrl".

_ page 1 " General" : showing some general inforamtion lile the total num of employees , the num of males , num of females , num of employees which need to promotion or don't need,the num of employees who will be retrenched or will not be retrenched and the num of employees who work over time or not.

![page 1](https://github.com/user-attachments/assets/14e4779b-0515-40f5-8c49-9cb3e194f320)


_ page 2 "Details" : showing detailed informations about promoted and not promoted employees and the employees who will be retrencehed and who will not be retrencehd. 

![page 2](https://github.com/user-attachments/assets/7b89a477-a935-4542-8765-d9ee10324372)


_page 3 "Service benefits " : showing the employees who need to promotion but they will be retrencehed so they deserve the huge end of service bonus.

![ppage 33](https://github.com/user-attachments/assets/39ddc10b-595c-46f4-bf5a-b6732ee85b2d)


_page 4 "Details in departements" : showing detailed informations about promoted and not promoted employees and the employees who will be retrencehed and who will not be retrencehd in each departement. 

![page 4](https://github.com/user-attachments/assets/889a48ac-7a2f-4b7e-9a60-5cb0ce7f4bac)


_page 5 "Salaries" : showing the top 10 employees with salaries in each department. 

![Page 5](https://github.com/user-attachments/assets/bf7df267-5ddd-4c8f-9ced-e3cf809ca118)


page 6 "Performance & Statisfaction" : showing the num of employees in each performance rating and in each job satisfaction rating.

![Page 6](https://github.com/user-attachments/assets/71e31e51-56ae-4f16-b00d-f10877546f52)

Contribution :
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
We welcome contributions from other developers. You can open a pull request to submit improvements or fixes to the report.


Contact :
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
If you have any questions or inquiries, please contact us via email at muhmdkhaled05@gmail.com.
