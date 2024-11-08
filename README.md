# M7Ray-HR-Analysis

- PROJECT OVERVIEW

  Using important data and visualizations, this Power BI dashboard offers a thorough examination of employee attrition inside an organization in order to spot trends and      insights. The dashboard is set up to provide a brief but thorough overview of the aspects influencing employee turnover, broken down into job-related and demographic        factors.

  For Further analysis, we added a conditional column as:

  = Table.AddColumn(#"Changed Type1", "AttritionCount", each if [Attrition] = "Yes" then 1 else 0)

    The data set contains the following parameters:
    * Demographics: Age, Gender, Marital Status, Education Level, Education Field.
    * Job Attributes: Job Role, Job Level, Department, Job Satisfaction, Environment Satisfaction, Job Involvement.
    * Financial and Work Conditions: Monthly Income, Salary Slab, Daily and Monthly Rates, Distance from Home.
    * Company Engagement: Years at Company, Years in Current Role, Total Working Years, Years Since Last Promotion, Years With Current Manager, Work-Life Balance.
    * Performance and Ratings: Performance Rating, Percent Salary Hike, Stock Option Level, Training Times Last Year.

- INSIGHTS

  * Attrition Rate by Age Group: The age group 26-35 has the highest attrition, indicating younger employees may leave more frequently.
  * Education and Attrition: Employees from Life Sciences and Medical backgrounds show higher attrition rates, hinting at possible dissatisfaction or better opportunities 
    elsewhere.
  * Role-Specific Attrition: Job roles like Laboratory Technician, Sales Executive, and Research Scientist show higher attrition, indicating areas where retention efforts 
    may be needed.
  * Salary and Tenure Correlation: Analysis of the average salary and tenure can provide insights into whether compensation or long-term growth opportunities impact 
    turnover.

- CONCLUSION

  This dashboard is a useful tool for determining and mitigating the risks associated with staff attrition. The dashboard gives HR and management useful information to 
  create focused retention plans and raise employee happiness by examining variables like age, job function, education, and tenure.


<img width="581" alt="pic1" src="https://github.com/user-attachments/assets/1adb07f1-fa3c-444a-9e9f-8a137aafa3c1">

<img width="581" alt="pic2" src="https://github.com/user-attachments/assets/e5cd5dad-ea46-4203-9965-74081a45eb0a">


#



#
