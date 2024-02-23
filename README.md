## Introduction
The dataset was released by Aspiring Minds from the Aspiring Mind Employment Outcome 2015 (AMEO). The study is primarily limited  only to students with engineering disciplines. The dataset contains the employment outcomes of engineering graduates as dependent variables (Salary, Job Titles, and Job Locations) along with the standardized scores from three different areas – cognitive skills, technical skills and personality skills. The dataset also contains demographic features. The dataset  contains  around  40 independent variables and 4000 data points. The independent variables are both continuous and categorical in nature. The dataset contains a unique identifier for each candidate.
## Business Problem
The focus of this study is on certain groups of graduates in computer science and engineering in order to better understand the unique job issues they confront. For instance, certain job specializations pay better than others.
## Objectives of the Project
* To unravel employment outcomes of computer science and engineering graduates
* identify possible factors that influence compensation.
## Research Question
* After doing your Computer Science Engineering if you take up jobs as a Programming Analyst, Software Engineer, Hardware Engineer and Associate Engineer you can earn up to 2.5-3 lakhs as a fresh graduate?
## Exploratory Data Analysis
### Data Cleaning Steps
* The data contains no duplicate values. 
* I removed 0  values from the graduation year column
* I Converted 'ID', '12graduation', 'CollegeID', 'CollegeTier', 'CollegeCityID', 'CollegeCityTier', 'GraduationYear' columns to object data types
* I removed outliers from the salary column. 
* I replaced negative values in the AMCAT scores columns with nan
* I corrected spelling errors and replaced negative and 0 values with nan in the object columns - 'Designation', 'JobCity', '10board','12board'
### Data Manipulation Steps
* I created 'age_at_hire' column by subtracting  Date of joining (DOJ) from Date of Birth (DOB) and filtered data for age values of 18 and above.
### Univariate analysis steps
* I plotted a frequency distribution of each numerical column.
* I plotted the count of each categorical variable in the dataset
### Bivariate analysis steps
* I identified relationships between numerical columns using a heatmap.
* I identified the relationship  between degree attained and salary.
* I identified the relationship between each degree attained with gender and salary.
* I Identified the relationship between college level and salary
* I Identified the relationship between gender and salary.
* I plotted a count of each specialization based on gender.
* Investigated the compensation plans of certain job specialization. I visualized the salary distribution of job designations - Programming Analyst, Software Engineer, Hardware Engineer and Associate Engineer
## Insights Findings
![image](https://github.com/amiegirl/Analysis_of_AMCAT_Data/assets/81017006/3b6727a0-75c8-4d26-b6d2-ec7e6d075d78)<br>
A normal distribution can be seen in the majority of the numerical variables. Few have a right skew.<br>
Employee salaries often range from 100,000 to 400,000.<br>
Ages 21 to 24 make up the majority.<br>
The majority of employees' college GPAs range from 62 to 80.<br>
<br>
<br>
![image](https://github.com/amiegirl/Analysis_of_AMCAT_Data/assets/81017006/c649abaf-36ec-402b-8b46-bfa30b9ad409)<br>
The majority of workers hold a bachelor's degree. Few people possess an MCA, an M.Tech, or an M.E.<br>
<br>
<br>
![image](https://github.com/amiegirl/Analysis_of_AMCAT_Data/assets/81017006/5b189685-b310-47ac-b068-867833335a5e)<br>
The most popular specialization among workers is electronics and communication engineering, which is followed by computer science and engineering and information technology.
<br>
<br>
![image](https://github.com/amiegirl/Analysis_of_AMCAT_Data/assets/81017006/a093d2a2-2771-4c4a-99ce-a69dc1c794d8)<br>
The most prevalent designation among workers is software engineering.<br>
<br>
<br>
![image](https://github.com/amiegirl/Analysis_of_AMCAT_Data/assets/81017006/9282c9b5-27d9-45f7-a753-fd8619292c3f)<br>
The majority of the workforce is based in Bangalore.<br>
<br>
<br>
![image](https://github.com/amiegirl/Analysis_of_AMCAT_Data/assets/81017006/603ee3bc-956c-4cc1-a369-98f2e8c1236b)<br>
There heatmap shows no relationship between the salary and the candidate's scores, age, or other numerical factors.<br>
<br>
<br>
![image](https://github.com/amiegirl/Analysis_of_AMCAT_Data/assets/81017006/35f772f3-3304-4f10-8d32-b53b8d19919b)<br>
The average salary of employees holding a master's degree in Technology or Engineering is higher.<br>
<br>
<br>
![image](https://github.com/amiegirl/Analysis_of_AMCAT_Data/assets/81017006/b86f7ced-4308-49d9-bf21-a96bf2c6d761)<br>
Workers with tier 1 college degrees typically earn higher money.<br>
<br>
<br>
![image](https://github.com/amiegirl/Analysis_of_AMCAT_Data/assets/81017006/bf54f1f9-ee05-4443-b2b3-d6559c3331b2)<br>
On average, females earn less money than males.<br>
<br>
![image](https://github.com/amiegirl/Analysis_of_AMCAT_Data/assets/81017006/fad2377b-ef51-44de-accf-f68962ec5c4d)<br>
In comparison to males, females who hold a master's degree earn more money.<br>
<br>
<br>
![image](https://github.com/amiegirl/Analysis_of_AMCAT_Data/assets/81017006/90afc3f2-17a3-40ed-9a9b-a91e9b0aa2af)<br>
In every specialization but biotechnology, where there are more females, males predominate, whereas in information and communication technology, only females are found.
<br>
<br>
![image](https://github.com/amiegirl/Analysis_of_AMCAT_Data/assets/81017006/74601076-0f6e-483c-a6bb-6a0ef765883c)<br>
Programmer analysts, software engineers, hardware engineers, and associate engineers earn up to 2.5 and 3 lakhs, with software engineers being the highest earners<br>
<br>
<br>
## Conclusion
The findings from the Analysis of Employment outcomes of computer science and engineering graduates shows us the salary for different job specializations varies. Pay is not influenced by age or scores.

While males predominate in most specializations, there are more females in biotechnology and solely females in information and communication technology. Workers with tier 1 college degrees typically earn higher money. The degree earned plays a significant role in determining compensation; those with master's degrees in Technology or Engineering typically earn more money. Even still, on average, females earn less money than males. In comparison to males, females who hold a master's degree earn more money.

Salary comparison indicates that programmer analysts, software engineers, hardware engineers, and associate engineers earn up to 2.5 and 3 lakhs, with software engineers being the highest earners.
