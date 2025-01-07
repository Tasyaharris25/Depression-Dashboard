# Depression-Dashboard

Data source : Kaggle - [Student Depression Dataset](https://www.kaggle.com/datasets/hopesb/student-depression-dataset)

## Introduction
Mental health is a critical aspect of well-being, especially among individuals facing academic, financial, and work-life pressures. This uses survey data to explore factors contributing to depression and suicidal tendencies among highschool students, college students, as well as employee, aiming to uncover actionable insights for fostering healthier environments. 

## Objective 
The primary objectives of this analysis are:

1. To identify the percentage of respondents experiencing depression.

2. To examine correlations between depression and key contributing factors, including financial stress, work pressure, and work hours.

3. To assess sleep patterns and their impact on mental health.

4. To provide actionable insights for stakeholders (e.g., educators, counselors, and policymakers) to address mental health challenges effectively.

## Analysis

<img width="679" alt="image" src="https://github.com/user-attachments/assets/4ffb4195-6a42-4fe2-8149-84036e7da0f7" />
Depression Trends Dashboard

1. Depression Prevalence
   
Using DAX formula to calculate percentage of respondents who experience depression: 
<img width="590" alt="image" src="https://github.com/user-attachments/assets/c6e64a08-4ee0-4dc4-9769-736cd44f43e9" />

Key Metric: 59% of respondents reported experiencing depression.

This figure highlights a significant mental health concern, with more than half of the surveyed population affected.

2. Suicidal Thoughts Prevelance

Since the data of suicidal thoughts in data source using categorical data, a new column was created to record the suicidal thoughts data using boolean type. 
<img width="593" alt="image" src="https://github.com/user-attachments/assets/4b859a1d-7a68-4fab-9cde-66ac553bfaf6" />

DAX formula to calculate percentage of respondents who have suidical thoughts: 
<img width="566" alt="image" src="https://github.com/user-attachments/assets/c0aa27e8-c689-43a4-918e-e32b6c95f6d0" />

The result shows 63% of the respondents have thought about suicide, this percentage is more that depression respondents. This indicate that there are some respondents who did not have depressio but have suicidal thought. 

3. Financial Stress and Academic Pressure

<img width="142" alt="image" src="https://github.com/user-attachments/assets/46a02d14-4fc5-4cf2-99e8-990d24f5258a" />

- The scatter chart shows the relationship between financial stress and academic pressure among individuals who reported experiencing depression.

- There is a positive correlation between financial stress and academic pressure among depressed respondents, indicates that as financial stress increases, academic pressure also tends to rise.

- Each size of data point shows the amount of respondents experiencing depression, with their respective levels of financial stress (X-axis) and academic pressure (Y-axis)

4. Sleep Duration and Depression

<img width="140" alt="image" src="https://github.com/user-attachments/assets/1792b66b-2cb8-47eb-ad29-aacd33ce3abe" />

Those with less than 5 hours of sleep per night showed higher rates of depression, while those who slept 7-8 hours reported lower rates.

5. Age Groups

- Age Groups:
Age Groups column was created to group the age data so that it will be easier to analyze.
<img width="656" alt="image" src="https://github.com/user-attachments/assets/6a898f47-7ecf-4309-b88d-e3d65d3dd838" />

- Respondents aged 20-30 formed the largest group experiencing depression.
- Individuals above 40 had the lowest reported rates of depression.

6. Family History
   <img width="127" alt="image" src="https://github.com/user-attachments/assets/012837c5-62bd-4876-9ed9-4c3d5c5b8624" />

The pie chart shows the respondents with depression by family history of mental illness, the result shows there is a slight difference between respondents who experience depression with family history and without family history, by 50.64% and 49.36% respectively.

7. Work Hours

<img width="133" alt="image" src="https://github.com/user-attachments/assets/d84e384b-4369-4cc3-b262-9ef3c6b08265" />

The chart appears to show a general upward trend in the count of depression as the number of work/study hours increases. This suggests that a higher number of work/study hours might be associated with a greater prevalence of depression.

8. Gender
   <img width="111" alt="image" src="https://github.com/user-attachments/assets/4b915d3d-4f9e-493c-b3c4-fc58fa52cb5a" />

From this graph, it shows that there are male respondents with depression compared to female. 

9.  Slicers

The dashboard includes interactive slicers that allow users to filter results based on:

- Academic Level ( Highscool Student, College Student, and Working)
  Academic Levels column was created to group academic or profession data so that it will be easier to analyze.
<img width="688" alt="image" src="https://github.com/user-attachments/assets/215968ec-b12c-403d-9f8c-d3145ba03e38" />

- Age Group ( 20-30, 30-40, Above 40)
- Gender (Male, Female)
These slicers make the dashboard highly flexible and enable dynamic exploration of the data.


## Insights and Recommendations

- Targeted Financial Support:

  Provide scholarships, grants, and financial counseling programs to alleviate financial stress.

- Work-Life Balance Programs:

  Introduce flexible work schedules and stress-reduction initiatives to improve work satisfaction.

- Encouraging Healthy Sleep Habits:

  Promote awareness campaigns about the importance of 7-8 hours of sleep for better mental health.

- Early Intervention for Younger Individuals:

  Provide mental health support systems for high school students, who report higher rates of depression.

- Awareness Campaigns:

  Conduct programs to reduce the stigma around depression and encourage seeking help.

## Conclusion

This analysis underscores the importance of addressing depression and mental health challenges across diverse groups. By leveraging data-driven insights, stakeholders can implement targeted interventions to improve overall mental well-being.

