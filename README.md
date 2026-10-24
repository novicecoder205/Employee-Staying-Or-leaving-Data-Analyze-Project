### Project Overview:

This project is a machine learning model that aims to predict the rates of Employees, would stay or leaving their previous workplace, base on a numbers of factors and data from field that would effect the employees in some ways.

#### 1. Problem Statement:

. The goals of the project is to develops a machine learning model that would predict why employee choose to sign off from the company they works for, base on the correlation with other factions such as salary, years of experience, whether and for long does employee goes without being on a project.  

#### 2. Dataset + Analysis:

. Dataset: 

This dataset can be used for various HR and workforce-related analyses, including employee retention, salary structure assessments, diversity and inclusion studies, and leave pattern analyses. Researchers, data analysts, and HR professionals can gain valuable insights from this dataset.

Link: https://www.kaggle.com/datasets/tawfikelmetwally/employee-dataset

##### . Analysis:

##### 1. What are the common range of age for employees in this company?
<img width="588" height="441" alt="image" src="https://github.com/user-attachments/assets/be3cf548-560a-42c9-b9b4-108dfb99edd6" />

. Explanation: Most employees are between 24 and 40 years old, with age 28 having the highest frequency.

##### 2. What are the gender dispersity for this company employees?
<img width="629" height="483" alt="image" src="https://github.com/user-attachments/assets/646054f5-ef1b-40c6-af9e-22e89956457e" />

###### . Explaination: 

The chart shows that male employees make up a larger proportion of the workforce than female employees, with approximately 1,520 males compared to 1,240 females.

##### 3. What are the distribution of Experience of staff in their current domain, counting in years?
<img width="512" height="442" alt="image" src="https://github.com/user-attachments/assets/a9ac0a0b-8936-442d-a356-75f5a1bdf4de" />

###### . Examination:

. Minimum Experience are approximately 0 years.

. First quartile (Q1): 1 year, meaning 25% of employees have 1 year or less of experience.

. Median (Q2): 2 years, meaning 50% of employees have 2 years or less of experience, while the other 50% have 2 years or more.

. Third quartile (Q3): 4 years, meaning 75% of employees have 4 years or less of experience.

. Maximum experience: Approximately 7 years.

. The Interquartile range (IQR): 4-1=3 years, The middle 50% of employees have between 1 and 4 years of experience.

Right-skewed distribution: The median is closer to Q1 than to Q3, and the right whisker is longer than the left whisker. This suggests a positively skewed distribution, with some employees having relatively higher domain experience.

Concentration of experience: Most employees have between 1 and 4 years of experience in their current domain, indicating that the workforce is primarily composed of employees with relatively limited to moderate domain experience.

Overall, the chart indicates that employees typically have around 2 years of experience in their current domain, with the central 50% having between 1 and 4 years. Experience ranges from approximately 0 to 7 years, and the longer upper whisker suggests some variation toward higher experience levels.

##### 5. How are the Experience in the current profession domain varies across different age group within the employee population?

<img width="777" height="350" alt="image" src="https://github.com/user-attachments/assets/446f58ca-1e9c-4f10-911f-50b98df0026d" />

###### . Explaination:

The boxplot illustrates the distribution of experience in the current domain across different age groups. For most employees aged 28–41, the median domain experience remains approximately 2–3 years, indicating that experience in the current domain does not increase consistently with age. 

Considerable variation is observed within several age groups, suggesting differences in career trajectories and the timing of entry into the current domain. A potential outlier is also observed at age 35, with approximately 7 years of domain experience. 

Overall, the results suggest that age alone may not be a reliable indicator of experience in the current domain. Further analysis, including the number of observations per age group and a correlation analysis, would help clarify the relationship between age and domain experience.

##### 6 . What are the salary tier according to age group for employee?

<img width="585" height="445" alt="image" src="https://github.com/user-attachments/assets/9a998447-a3f8-4043-901b-aa49bc81ca47" />

All payment tier (again, 1 is the lowest salary and 3 is the highest) share a common trend.

Those of Age around 25 to 30 hold the highest population of each receives payment tier, showing that most employee would be around that age group.

Payment tier 1 hold the highest population in comparison to the population of employee receiving tier 2 and tier 3 salary.

##### 6 . What are the salary tier according to age group for employee?

<img width="647" height="507" alt="image" src="https://github.com/user-attachments/assets/94e50cce-4501-4f7d-a102-a0af57190312" />

The violin plot shows that employee ages are broadly similar across all three payment tiers, with median ages increasing slightly from approximately 28 to 30 years. The substantial overlap suggests that age alone may not strongly distinguish payment tiers. Further analysis is needed to determine whether this difference is statistically significant.

##### 7 . What are the percentage of employees choosing to leave the company in each cities?

<img width="601" height="501" alt="image" src="https://github.com/user-attachments/assets/6ada2e28-cd5d-42d6-87c6-7f84ebbe39e7" />

1. Pune may have a retention problem. Approximately half of its employees have left, which is substantially higher than in the other two cities. The company should investigate possible causes, such as compensation, workload, career development, management practices, or employee satisfaction.

2. Bangalore has the largest workforce. It has a high absolute number of departures, but this is partly explained by its larger employee population. Its attrition rate is a better measure for comparing performance with other branches.

3. New Delhi and Bangalore have similar retention patterns. Both branches retain roughly two-thirds of their employees, based on the approximate chart values. The company could investigate whether their retention practices offer lessons that could be applied in Pune.

##### 8 . What are the experiences between males and females staff in current domain?

<img width="567" height="452" alt="image" src="https://github.com/user-attachments/assets/23402dce-89f0-4036-8ade-76e2d9b0ca30" />

1. Female employees have a higher median experience level:
The female median is approximately 3, compared with 2 for male employees. This indicates that the midpoint of the female experience distribution is higher. It may suggest differences in hiring patterns, employee tenure, job assignments, or workforce composition, but the chart alone cannot explain the reason.

2. Both groups show similar variability:
The boxes extend from 1 to 4 for both genders, and both groups have the same overall range. This suggests similar variability in the central portion of the experience distributions. However, the full distributions could still differ in other ways.

3. Experience levels overlap considerably:
Both groups cover the range from 0 to 7. There is no clear separation between the groups based on this chart. Many male and female employees may have similar experience levels.

##### 8 . What are the rate of employees recruitment rates?

<img width="625" height="425" alt="image" src="https://github.com/user-attachments/assets/d3c35fc2-503b-436b-a1eb-45ab8769f815" />

The chart illustrates the annual distribution of new employees joining the company between 2012 and 2018. Recruitment generally increased from 2012 to 2015, reaching approximately 465 new employees in 2015, before declining in 2016. The company recorded its highest number of new hires in 2017, with approximately 660 employees, followed by a sharp decrease to around 240 employees in 2018. These fluctuations suggest that the company's recruitment activity varied considerably over the period, potentially reflecting changes in workforce demand or business expansion. Further investigation would be required to determine the underlying reasons for these changes.

#### 3. Machine Learning Models:



#### 4. Model Evaluation:

MSE and RMSE score:


