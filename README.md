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

. Explanation: 

The histogram shows that employees are approximately 22–41 years old, with most concentrated between 25 and 30, particularly around age 28. 

The number of employees aged 31–40 remains relatively stable, indicating a mix of young and experienced employees. Overall, the organization has a relatively young workforce, highlighting the importance of employee retention, career development, and knowledge sharing.

##### 2. What are the gender dispersity for this company employees?
<img width="629" height="483" alt="image" src="https://github.com/user-attachments/assets/646054f5-ef1b-40c6-af9e-22e89956457e" />

###### . Examination:

The chart shows that male employees make up a larger proportion of the workforce than female employees, with approximately 1,520 males compared to 1,240 females.

##### 3. What are the distribution of Experience of staff in their current domain, counting in years?
<img width="512" height="442" alt="image" src="https://github.com/user-attachments/assets/a9ac0a0b-8936-442d-a356-75f5a1bdf4de" />

###### . Examination:

Minimum Experience: Approximately 0 years.

First Quartile (Q1): 1 year, meaning 25% of employees have 1 year or less of experience.

Median (Q2): 2 years, meaning half of the employees have 2 years or less of experience.

Third Quartile (Q3): 4 years, meaning 75% of employees have 4 years or less of experience.

Maximum Experience: Approximately 7 years.

Interquartile Range (IQR): 3 years (4 − 1), meaning the middle 50% of employees have between 1 and 4 years of experience.

Distribution: The data is right-skewed, as the right whisker is longer than the left. This indicates that some employees have considerably more experience than others.

Concentration of Experience: Most employees have between 1 and 4 years of experience in their current domain, suggesting a workforce with limited to moderate experience.

Overall: The chart shows that employees typically have around 2 years of experience, with most falling between 1 and 4 years. Experience ranges from approximately 0 to 7 years, with a few employees having higher levels of experience.

##### 5. How are the Experience in the current profession domain varies across different age group within the employee population?

<img width="777" height="350" alt="image" src="https://github.com/user-attachments/assets/446f58ca-1e9c-4f10-911f-50b98df0026d" />

###### . Examination:

The boxplot shows the distribution of current domain experience across different age groups. For most employees aged 28–41, the median experience is around 2–3 years, suggesting that domain experience does not consistently increase with age.

Variation: Several age groups show considerable differences in experience, possibly reflecting different career paths and the timing of entry into their current domain. An outlier is also observed at age 35, with approximately 7 years of experience.

Overall: The results suggest that age alone is not a reliable indicator of domain experience. Further analysis, such as examining the number of employees in each age group and conducting a correlation analysis, could provide a clearer understanding of their relationship.

##### 6 . What are the salary tier according to age group for employee?

<img width="585" height="445" alt="image" src="https://github.com/user-attachments/assets/9a998447-a3f8-4043-901b-aa49bc81ca47" />

###### . Examination:

All payment tier (again, 1 is the lowest salary and 3 is the highest) share a common trend.

Those of Age around 25 to 30 hold the highest population of each receives payment tier, showing that most employee would be around that age group.

Payment tier 1 hold the highest population in comparison to the population of employee receiving tier 2 and tier 3 salary.

##### 6 . What are the salary tier according to age group for employee?

<img width="647" height="507" alt="image" src="https://github.com/user-attachments/assets/94e50cce-4501-4f7d-a102-a0af57190312" />

###### . Examination:

The violin plot shows that employee ages are broadly similar across all three payment tiers, with median ages increasing slightly from approximately 28 to 30 years. The substantial overlap suggests that age alone may not strongly distinguish payment tiers. Further analysis is needed to determine whether this difference is statistically significant.

##### 7 . What are the percentage of employees choosing to leave the company in each cities?

<img width="601" height="501" alt="image" src="https://github.com/user-attachments/assets/6ada2e28-cd5d-42d6-87c6-7f84ebbe39e7" />

###### . Examination:

A. Pune: Has a potential retention problem, with approximately half of its employees leaving. The company should investigate possible causes, such as salary, workload, and career development.

B. Bangalore: Has the largest workforce and the highest number of departures, partly due to its larger employee population. Its attrition rate provides a better comparison.

C. New Delhi: Has a retention pattern similar to Bangalore, retaining roughly two-thirds of its employees. Their retention practices could provide useful lessons for improving Pune's retention.

##### 8 . What are the experiences between males and females staff in current domain?

<img width="567" height="452" alt="image" src="https://github.com/user-attachments/assets/23402dce-89f0-4036-8ade-76e2d9b0ca30" />

###### . Examination:

A. Higher Female Median: Female employees have a higher median experience (3 years) than males (2 years), suggesting slightly higher experience levels.

B. Similar Variability: Both groups have an IQR of 1–4 years and the same overall range, indicating similar experience distributions.

C. Considerable Overlap: Both groups range from 0 to 7 years of experience, showing no clear separation between male and female employees.

##### 9 . What are the rate of employees recruitment rates?

<img width="625" height="425" alt="image" src="https://github.com/user-attachments/assets/d3c35fc2-503b-436b-a1eb-45ab8769f815" />

###### . Examination:

The chart illustrates the annual distribution of new employees joining the company between 2012 and 2018. Recruitment generally increased from 2012 to 2015, reaching approximately 465 new employees in 2015, before declining in 2016. 

The company recorded its highest number of new hires in 2017, with approximately 660 employees, followed by a sharp decrease to around 240 employees in 2018. These fluctuations suggest that the company's recruitment activity varied considerably over the period, potentially reflecting changes in workforce demand or business expansion. 

Further investigation would be required to determine the underlying reasons for these changes.

##### 10 . What are average experience in the field between female and male employees across three educational degree, Bachelors, Master and PHD. 

<img width="581" height="495" alt="image" src="https://github.com/user-attachments/assets/a080934d-4314-44c6-8ef1-e490e026fbae" />

###### . Examination:

A. Experience and Education: Average domain experience increases with education level, from Bachelor's to Master's to PhD, suggesting a positive association.

B. Gender Differences: Females have slightly higher average experience at the Bachelor's and Master's levels, while the PhD difference is unclear.

C. Highest Experience: PhD holders have the highest average domain experience across both genders.

##### 11 . What are the distribution of employees' experience in their current domain across three cities (Bangalore, Pune, and New Delhi), categorized by gender (Male and Female).

<img width="745" height="235" alt="image" src="https://github.com/user-attachments/assets/28241253-42bc-44e6-9663-7290299f9826" />

A. Workforce Experience: Most employees across the three cities have low-to-moderate domain experience, suggesting many are still developing their expertise.

B. Workforce Size: Bangalore has a noticeably larger workforce than Pune and New Delhi.

C. Gender Representation: Both genders are represented across experience levels, but the chart does not confirm balanced representation.

D. Experienced Employees: Few employees have more than five years of experience, which may be worth investigating further.

#### 12. What are the average age of the employees joining the company in the company three banches, Bangalore, New Delhi, and Pune?

<img width="577" height="422" alt="image" src="https://github.com/user-attachments/assets/cb0bce62-b71f-4cd5-85b8-e5aec4340b34" />

Bangalore: Employees joining the company are generally older, with an average age of around 31–32 years, thus they have the oldest new employee. 

New Delhi: Employees are generally younger, with an average age of around 29–30 years. However, their average age increases significantly in 2017, thus they have the youngest new employees.

Pune: Employees have an average age of around 30–31 years, with relatively small changes over the years, and the age gap stay relatively even.

#### 3. Machine Learning Models:

##### Repeat Goal:

Using ML models to figure out whether an employee will stay or leave the company, bases on the employee characteristics on the dataset. 

#### 1) Logistic Regression:

Logistic Regression predicts the probability that an employee belongs to one of two categories, 0 = stay, 1 = leave.

The model uses a mathematical function to calculate the probability of leaving based on employee characteristics.

What Logistic Regression learn are:

Does a lower PaymentTier associate with a higher probability of leaving?

Does being EverBenched associate with leaving?

Does experience in the current domain influence the prediction?

The Advantage of this model is it's easy to understand as data, fast to trains, and works well enough as a baseline models.

The problem with this model is it's assumes a relatively simple relationship between features and the log-odds of leaving. It's will also not may not capture complicated relationships between employee characteristics, and can not underperform when the dataset has complex nonlinear patterns well. 

#### 2) KNeighbors Classifier:

#### 3) Decision Tree Classifier:

#### 4) Random Forest Classifier:

#### 4. Model Evaluation:

MSE and RMSE score:


