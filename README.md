# Student Performance Analysis (SQL)

## 🗝️ Overview
This project investigates the factors influencing student success using a dataset containing study habits, sleep patterns, attendance, tutoring sessions, and extracurricular activities. By analyzing these variables, the goal is to identify key drivers of high exam scores and provide actionable insights for students and educators.

## 🎯Research Questions
1. Do more study hours and participation in extracurricular activities lead to better exam scores?  
2. Is there an optimal range of study hours for maximum academic performance?  
3. How does sleep affect exam results?  
4. What is the impact of tutoring sessions on student performance?  
5. How do combined factors (attendance, study hours, tutoring, and extracurricular activities) influence exam outcomes?  

## ✅Methodology
- SQL queries were used to clean, verify, and analyze the data.  
- Window functions (DENSE_RANK()) were applied to rank students' exact scores.  
- Correlation analysis was conducted to measure the strength of relationships between variables and exam scores.  

## 🧩Key Findings
- **Attendance** and **study hours** are the strongest predictors of exam performance.  
- Students studying **16+ hours per week** achieve higher scores.  
- Sleep hours have minimal impact on exam results.  
- Up to **6 tutoring sessions** help improve performance. 
- Combining **high attendance** with **high study hours** yields the best outcomes, while moderate attendance or study alone has less effect.  

## 🧭Conclusion
To maximize academic success, students should prioritize consistent attendance and structured study routines. Tutoring and extracurricular activities can provide additional support, but they are secondary to the core drivers of performance. 
Educators should focus on fostering discipline and regular participation to help students reach their full potential.

## 🛠️Technologies
- SQL (PostgreSQL environment in DataCamp)  
- Jupyter Notebook (.ipynb)
