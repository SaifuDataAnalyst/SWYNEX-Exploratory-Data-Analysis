# SWYNEX Technologies — Task 2: Exploratory Data Analysis

## Student Performance Dataset — Mathematics

### Internship

## Data Analyst Internship — SWYNEX Technologies

### Task

Task 2 — Exploratory Data Analysis (EDA)

---

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Student Performance Dataset — Mathematics.

The objective is to explore the dataset, understand patterns and relationships between variables, and identify factors associated with students' final academic performance.

The analysis was performed using Python and standard data analysis and visualization libraries.

---

## Dataset Information

- Dataset: Student Performance Dataset — Mathematics
- Source: UCI Machine Learning Repository
- Total Students: 395
- Original Features: 33
- Target Variable: "G3" — Final Grade

The dataset contains information related to students' demographic characteristics, family background, study habits, previous academic performance, absences, and other factors.

---

## Objective

The main objectives of this EDA are:

- Understand the structure and distribution of the dataset.
- Analyze numerical and categorical variables.
- Study the distribution of final grades.
- Explore relationships between academic variables.
- Analyze the relationship between absences and final grades.
- Examine study time and previous failures in relation to final grades.
- Analyze differences across selected demographic and background variables.
- Identify important correlations with the final grade.
- Generate meaningful visualizations and insights.

---

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## EDA Performed

### The following analyses were performed:

1. Dataset loading and overview
2. Dataset structure analysis
3. Statistical summary
4. Categorical variable frequency analysis
5. Final grade ("G3") analysis
6. Grade correlation analysis ("G1", "G2", "G3")
7. Absences vs final grade analysis
8. Study time vs final grade analysis
9. Previous failures vs final grade analysis
10. Gender vs final grade analysis
11. School vs final grade analysis
12. Parents' education vs final grade analysis
13. Internet access vs final grade analysis
14. Absence group analysis
15. Numerical correlation matrix
16. Main EDA visualizations
17. Key EDA values and findings
18. Final EDA summary

---

## Key Findings

### Final Grade

- Average G3: 10.42
- Minimum G3: 0
- Maximum G3: 20

### Study Time

Study Time| Average G3
1| 10.05
2| 10.17
3| 11.40
4| 11.26

The highest average final grade in this dataset was observed for Study Time category 3.

### Previous Failures

Previous Failures| Average G3
0| 11.25
1| 8.12
2| 6.24
3| 5.69

Students with fewer previous failures generally showed higher average final grades in this dataset.

### Gender

Gender| Average G3
Female| 9.97
Male| 10.91

### School

School| Average G3
GP| 10.49
MS| 9.85

### Internet Access

Internet Access| Average G3
No| 9.41
Yes| 10.62

---

## Correlation Insights

The analysis showed the following correlations with the final grade ("G3"):

Variable| Correlation with G3
G2| 0.90
G1| 0.80
Medu| 0.22
Fedu| 0.15
studytime| 0.10
famrel| 0.05
absences| 0.03
freetime| 0.01
Walc| -0.05
Dalc| -0.05
health| -0.06
traveltime| -0.12
goout| -0.13
age| -0.16
failures| -0.36

The strongest positive relationships with "G3" were observed for "G2" and "G1", while "failures" showed a negative correlation with "G3".

These correlations describe relationships within the dataset and do not establish causation.

---

## Visualizations

The following visualizations were created and saved in the "EDA_Visualizations" folder:

- "G3_Distribution.png"
- "G2_vs_G3.png"
- "StudyTime_vs_G3.png"

Visualization 1 — Final Grade Distribution

Shows the distribution of students' final grades ("G3").

Visualization 2 — G2 vs Final Grade

Shows the relationship between second-period grade ("G2") and final grade ("G3").

Visualization 3 — Study Time vs Final Grade

Shows the average final grade across different study-time categories.

---

## Project Structure

SWYNEX_Task_2_EDA/
│
├── SWYNEX_Task_2_EDA.ipynb
├── student_mat_cleaned.csv
├── README.md
│
└── EDA_Visualizations/
    ├── G3_Distribution.png
    ├── G2_vs_G3.png
    └── StudyTime_vs_G3.png

---

## Conclusion

The Exploratory Data Analysis identified several important patterns in the Student Performance dataset.

Previous failures showed a negative relationship with final grade, while "G1" and "G2" showed strong positive relationships with "G3". Study time, parents' education, and internet access also showed associations with final academic performance.

The analysis and visualizations provide a useful understanding of the dataset and can serve as a foundation for further analysis and dashboard development.

Note: The observed relationships represent associations in the dataset and should not be interpreted as proof of causation.

---

### Task Status

Task 2 — Exploratory Data Analysis: Completed

Internship: SWYNEX Technologies
Role: Data Analyst Intern
