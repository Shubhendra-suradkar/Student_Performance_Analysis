# Student_Performance_Analysis
## Objective
This project analyzes factors influencing student performance using a dataset sourced from Kaggle. The goal is to identify key determinants of academic success and suggest interventions to enhance student outcomes.

## Data
The dataset contains information on 2392 students, including:

- *Demographic factors:* Age, gender, ethnicity, parental education
- *Academic performance:* Study time, absences, final grade
- *Extracurricular activities:* Tutoring, parental support, extracurricular participation, sports, music, volunteering

## Exploratory Data Analysis (EDA)
Our analysis revealed several key findings:

1. *GPA Distribution:* 
   - Student GPA exhibits a right skew, indicating more students achieve higher GPAs.
  
   ![Distribustion of GPA.png](https://raw.githubusercontent.com/Saurabh-Ghagare/Student_Performance_Data_Analysis/9dbadcbcc744f53555183dc12081c014345130ab/Distribustion%20of%20GPA.png)
   
2. *Gender and GPA:* 
   - The average GPA for male students is slightly higher than for females (1.92 vs. 1.89).

3. *Parental Education and GPA:* 
   - Students with parents having a "High School" education level have the highest average GPA (1.94).
   - There's a weak negative correlation between higher parental education and GPA.
   - ![Parental Education and GPA](https://raw.githubusercontent.com/Saurabh-Ghagare/Student_Performance_Data_Analysis/9dbadcbcc744f53555183dc12081c014345130ab/Average%20GPA%20by%20Parental%20Education%20level.png)

4. *Absences and GPA:* 
   - A strong negative correlation (-0.919) exists between absences and GPA, indicating a significant decrease in GPA with more absences.
   - ![Absences and GPA](https://raw.githubusercontent.com/Saurabh-Ghagare/Student_Performance_Data_Analysis/9dbadcbcc744f53555183dc12081c014345130ab/Relationship%20Between%20number%20of%20absences%20relate%20to%20GPA%20.png)

5. *Study Time Distribution:* 
   - Student study time tends to cluster around 3-5 hours weekly, with a larger portion dedicating less time and a smaller portion studying significantly longer.
   - ![Study Time Distribution](https://raw.githubusercontent.com/Saurabh-Ghagare/Student_Performance_Data_Analysis/9dbadcbcc744f53555183dc12081c014345130ab/Distibution%20of%20study%20time%20amongs%20students.png)

6. *Study Time and GPA:* 
   - There's a weak positive correlation (0.179) between study time and GPA, suggesting a slight increase in GPA with more study time.
   
## Key Insights
- *Parental Education and Weekly Study Time:* Strong predictors of student success.
- *Absences:* Have the most significant negative impact on academic performance.

## Recommendations
Based on these findings, we recommend:

1. *Support Programs for Students with Low Parental Education Backgrounds:*
   - Implementing academic and mentoring support programs to help bridge the educational gap.
   
2. *Strategies to Improve Attendance:*
   - Developing policies and interventions to reduce student absences, given their strong negative impact on GPA.

3. *Encouraging Increased Study Time:*
   - Offering resources and programs to support and encourage students to increase their study time, particularly for those studying less than 3 hours weekly.

## Future Work
This project serves as a starting point for further investigation into student performance factors. Future work could involve building predictive models or analyzing additional datasets to gain deeper insights.
