# ?? Student Performance Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Analysis-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge\&logo=python\&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)

## ?? Project Overview

This project analyzes the academic performance of **1,000 students** using Python and Power BI.

The analysis explores student scores in **Math, Reading, and Writing** and examines how performance varies across demographic, socioeconomic, and test-preparation factors.

### ?? Objectives

* Analyze student performance across the three subjects
* Identify patterns in Math, Reading, and Writing scores
* Compare performance across gender groups
* Examine performance by lunch type
* Analyze the relationship between test preparation and scores
* Create overall performance metrics
* Build visualizations and an interactive Power BI dashboard

---

## ?? Business Questions

This analysis is designed to answer practical questions that educators, school administrators, and education stakeholders may ask:

1. **Which subject shows the highest and lowest average student performance?**

2. **How does student performance differ by gender?**

3. **Do students who completed the test preparation course perform differently from those who did not?**

4. **How does performance vary between Standard and Free/Reduced lunch groups?**

5. **Does parental education level appear to be associated with student performance?**

6. **Which demographic groups have the highest and lowest average scores?**

7. **What percentage of students pass all three subjects?**

8. **How are students distributed across the different performance categories?**

9. **Which factors show the strongest relationship with overall student performance?**

10. **What patterns can be identified that may help schools better understand student academic outcomes?**

---

## ?? Dataset

The dataset contains **1,000 student records** and includes the following variables:

| Column                        | Description                                    |
| ----------------------------- | ---------------------------------------------- |
| `gender`                      | Student gender                                 |
| `race/ethnicity`              | Student race/ethnicity group                   |
| `parental level of education` | Parent's highest education level               |
| `lunch`                       | Standard or free/reduced lunch                 |
| `test preparation course`     | Whether the student completed test preparation |
| `math score`                  | Mathematics score                              |
| `reading score`               | Reading score                                  |
| `writing score`               | Writing score                                  |

### ?? Engineered Features

Additional features were created during the analysis:

| Feature                | Description                                             |
| ---------------------- | ------------------------------------------------------- |
| `total_score`          | Combined Math, Reading, and Writing scores              |
| `average_score`        | Average score across the three subjects                 |
| `performance_category` | Student performance classification                      |
| `pass_status`          | Pass/fail classification based on the defined threshold |

---

## ??? Tools & Technologies

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical analysis
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **SciPy** – Statistical analysis
* **Power BI** – Interactive dashboard development
* **Jupyter Notebook** – Analysis environment

---

## ?? Data Preparation & Analysis

The project includes:

* Data inspection and cleaning
* Missing-value checks
* Duplicate-value checks
* Descriptive statistical analysis
* Feature engineering
* Subject-level performance analysis
* Performance categorization
* Pass/fail analysis
* Group comparisons
* Data visualization

---

## ?? Key Findings

### ?? Subject Performance

The analysis compares student performance across:

* Mathematics
* Reading
* Writing

This helps identify differences in overall performance between the three subjects.

### ????? Gender Performance

The analysis shows differences in subject performance between male and female students, particularly across Reading, Writing, and Mathematics.

### ??? Lunch Type

Students were compared based on **Standard** and **Free/Reduced** lunch categories. The analysis shows differences in average academic scores between the two groups.

### ?? Test Preparation

Students who completed the test preparation course were compared with students who did not complete it. The analysis shows differences in average scores between the two groups.

### ?? Parental Education

Student performance was also examined across different parental education levels to identify patterns in academic outcomes.

### ? Pass/Fail Analysis

Using the defined passing criteria:

* **812 students (81.2%)** passed all three subjects
* **188 students (18.8%)** did not pass all three subjects

---

# ?? Dashboard & Visualizations

## 1. Student Performance Dashboard

The Power BI dashboard provides an overview of student performance using key performance indicators, charts, and interactive filters.

![Student Performance Analysis Dashboard](Student%20Performance%20Analysis%20Dasboard.JPG)

---

## 2. Gender Distribution

Shows the distribution of students by gender.

![Gender Distribution](Gender%20Distribution.JPG)

---

## 3. Average Score by Subject

Compares average performance across Math, Reading, and Writing.

![Average Score Bar Chart](Average%20Score%20Bar%20Chart.JPG)

---

## 4. Performance by Gender

Compares student performance across subjects by gender.

![Performance By Gender](Performance%20By%20Gender.JPG)

---

## 5. Performance by Lunch Type

Compares academic performance across lunch categories.

![Performance By Lunch](Performance%20By%20Lunch.JPG)

---

## 6. Student Performance Categories

Shows the distribution of students across the defined performance categories.

![Students Performance Categories](Students%20Performance%20Categories.JPG)

---

# ?? Repository Structure

```text
student-performance-analysis/
¦
+-- data/
¦   +-- StudentsPerformance.csv
¦
+-- notebooks/
¦   +-- Student_Performance_Analysis.ipynb
¦
+-- assets/
¦   +-- Student Performance Analysis Dasboard.JPG
¦   +-- Gender Distribution.JPG
¦   +-- Average Score Bar Chart.JPG
¦   +-- Performance By Gender.JPG
¦   +-- Performance By Lunch.JPG
¦   +-- Students Performance Categories.JPG
¦
+-- README.md
+-- requirements.txt
```

---

# ?? How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/singleme92/student-performance-analysis.git
```

### 2. Navigate to the project folder

```bash
cd student-performance-analysis
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/Student_Performance_Analysis.ipynb
```

---

# ?? Project Workflow

```text
Raw Dataset
     ?
Data Cleaning
     ?
Exploratory Data Analysis
     ?
Feature Engineering
     ?
Statistical Analysis
     ?
Data Visualization
     ?
Power BI Dashboard
     ?
Insights & Conclusions
```

---

# ?? Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Exploratory Data Analysis
* Statistical Analysis
* Feature Engineering
* Data Visualization
* Python Programming
* Pandas & NumPy
* Matplotlib & Seaborn
* Power BI Dashboard Development
* Data Storytelling
* Analytical Reporting
* Business Question Development

---

# ?? Author

## Jide Falowo

**Data Analyst | Data Science Enthusiast**

?? **GitHub:** [github.com/singleme92](https://github.com/singleme92)

?? **LinkedIn:** [linkedin.com/in/babajide-falowo-a59456281](https://linkedin.com/in/babajide-falowo-a59456281)

---

? If you find this project useful, feel free to explore the repository and give it a star.
