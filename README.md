# Project Title


# Salaries of Data field employees
## Problem Statement
This dashboard helps understand the salaries of data field employees for different types of companies in terms of size, different job titles, and different levels of experience. This dashboard is based on data for the last five years, and the source of the data used in this report is from https://www.kaggle.com/
### Steps followed 

 - Step 1 : Load data into Power BI Desktop, dataset is a csv file.
 - Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
 - Step 3 : Add a column to calculate the monthly salary
     % (salary_for_month='salaries (2)'[salary_in_usd]/12)
  ![لقطة شاشة 2024-05-29 085916](https://github.com/HASSN1421/Dashboard/assets/162873878/751630c2-1901-498d-86d5-d6892abcdc03)
- Step 4 : Add a column to calculate the monthly salary Change the data type
   - Step 5 : Add a column to calculate the salary in Saudi Riyals for the month


                   


 ![imge2](https://github.com/HASSN1421/Dashboard/assets/162873878/22f2f2f0-15f2-4ec9-8de8-648d79488a37)
- Step 6 : Create measures for calculate (AVG,MAX,MIN)value 
   
    
     
      
               %  avg = AVERAGE('salaries (2)'[salary_by_R])
               max = MAX('salaries (2)'[salary_for_month])
               min = MIN('salaries (2)'[salary_for_month])
- Step 7 : Replaceing value in (experience_level)column replace(M:Middle,E:Entry,S:Senior)
 - Step 8 : Replaceing value in (experience_level)column replace(M:Middle,E:Entry,S:Senior)
 - Step 9 : Create a graphic to describe average salaries for each year by graphic type Donut chart
 ![salary by years ](https://github.com/HASSN1421/Dashboard/assets/162873878/cb48b322-24d0-4b9b-8493-4a9bcac58818)

- Step 10 : create a grphic to describe average salaries by Experience levels by graphic …70dd768c-33cd-4d68-a2d5-78a6e00e1bb4)
- Step 13 : create a grphic to describe Count of job title by company size by graphic type Stacked column chart
![لقطة شاشة 2024-05-29 094731](https://github.com/HASSN1421/Dashboard/assets/162873878/11be8cf0-ce18-4fbf-9fae-aa43ebb581dc)
- Step 14 : create a grphic to describe - Step 11 : create a grphic to describe Average The salary  by company size by graphic type Area chart by graphic type Pie chart
![لقطة شاشة 2024-05-29 095057](https://github.com/HASSN1421/Dashboard/assets/162873878/1eb8bf27-8b9a-4b1b-a5c5-53c806d6ca36)
### Final format of the report
 ![last ](https://github.com/HASSN1421/Dashboard/assets/162873878/eb978cd2-4e39-496e-83a6-2381ed9d93fd)



