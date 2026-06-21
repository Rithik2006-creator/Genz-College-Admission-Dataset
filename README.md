# Student Admission Dataset - Exploratory Data Analysis (EDA)

## Overview

This project performs an Exploratory Data Analysis (EDA) on a large-scale student admission dataset containing **1,000,000 student records** and **20 features**. The objective is to understand the factors influencing college admission decisions and uncover patterns related to academic performance, extracurricular activities, personal attributes, and demographic characteristics.

---

## Dataset Information

### Dataset Summary

* **Rows:** 1,000,000
* **Columns:** 20
* **Target Variable:** `admission_status`
* **Data Type:** Numerical and Categorical

### Features

#### Identifiers & Demographics

* `student_id`
* `age`
* `gender`
* `state`

#### Academic Performance

* `high_school_gpa`
* `sat_score`
* `act_score`
* `attendance_rate`
* `ap_courses`

#### Extracurricular Activities & Engagement

* `extracurricular_count`
* `volunteer_hours`
* `leadership_positions`
* `coding_projects`
* `online_certifications`

#### Personal Attributes

* `social_media_hours`
* `essay_score`
* `recommendation_score`
* `interview_score`

#### Admission Outcome

* `admission_status`

---

## Project Objectives

* Analyze the distribution of student demographics and academic performance.
* Identify factors associated with admission decisions.
* Explore relationships between academic, extracurricular, and personal attributes.
* Detect trends across gender and state categories.
* Understand the overall characteristics of admitted and non-admitted students.

---

## Exploratory Data Analysis Performed

### Demographic Analysis

* Gender distribution
* Age distribution
* State-wise student representation

### Academic Performance Analysis

* GPA distribution
* SAT and ACT score distributions
* Attendance rate analysis
* AP course participation

### Extracurricular & Personal Attributes

* Volunteer hours
* Leadership positions
* Coding projects
* Online certifications
* Social media usage

### Admission Analysis

* Admission rate comparison
* Gender-wise admission trends
* Interview score analysis
* Academic performance comparison between admitted and non-admitted students

### Correlation Analysis

* Feature correlation matrix
* Relationship between variables and admission outcomes

---

## Key Findings

### Student Demographics

* Male students: **49.1%**
* Female students: **48.9%**
* Other gender identities: **2.0%**
* Age distribution is nearly uniform.
* Students are evenly distributed across states.

### Academic Performance

* Most students have a GPA between **3.0 and 3.5**.
* A smaller group achieves a perfect **4.0 GPA**.
* Attendance rates are generally high, clustering around **90–92%**.
* Many students maintain perfect attendance.

### Family Income

* Family income is heavily right-skewed with several high-income outliers.
* Median income provides a better representation of typical income levels than the mean.

### Admission Outcomes

* Approximately **88.54%** of students are admitted.
* Approximately **11.45%** are not admitted.
* Admission rates remain consistent across gender categories.
* Interview score distributions are similar among genders, indicating minimal demographic influence.

### Certifications & Student Engagement

* Most students complete **1–2 online certifications**.
* Participation decreases as the number of certifications increases.

### Social Media Usage

* Social media usage shows little relationship with GPA.
* Both high-performing and average students exhibit similar usage patterns.

### Correlation Analysis

* Most variables display weak correlations.
* Each feature contributes unique information and is not highly redundant.

---

## Admission Insights

Median-based comparisons of SAT scores and interview performance indicate that admitted students generally outperform non-admitted students.

However, the presence of high-scoring non-admitted students demonstrates that admissions are not determined by a single metric. Instead, admission decisions appear to follow a **holistic evaluation approach**, considering:

* Academic performance
* Extracurricular achievements
* Leadership experience
* Personal statements
* Recommendations
* Interview performance

---

## Final Conclusion

The dataset represents a balanced and diverse student population with minimal demographic bias. Academic and performance-related factors appear to be more informative than demographic characteristics when explaining admission outcomes.

The analysis suggests that admission decisions are primarily associated with student achievements, engagement, and overall performance rather than gender or geographic background. Additionally, the weak correlations among most features indicate that each variable contributes distinct information, making the dataset well-suited for predictive modeling and machine learning applications.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Future Work

* Build admission prediction models.
* Perform feature importance analysis.
* Compare multiple classification algorithms.
* Develop admission probability prediction systems.
* Create interactive dashboards for admission insights.

---

## Author

Student Admission Dataset - Exploratory Data Analysis Project
