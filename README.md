# Student Performance Analysis

## Overview

This repository contains an exploratory data analysis (EDA) project that I completed during my university studies. The project analyzes the **Student Performance Prediction** dataset from Kaggle to explore relationships between demographic characteristics and students' academic performance in mathematics, reading, and writing.

The primary goal of this project was to practice data exploration, visualization, and basic statistical analysis using Python.

> **Note:** This is an academic project that I keep as part of my learning journey. It does not reflect my current professional focus.

---

## Dataset

**Source:** https://www.kaggle.com/datasets/rkiattisak/student-performance-in-mathematics

The dataset contains information for **1,000 high school students** collected from three schools in the United States.

### Features

| Column | Description |
|---------|-------------|
| Gender | Student's gender |
| Race/Ethnicity | Student's ethnic group |
| Parental Level of Education | Highest education level of the parents |
| Lunch | Standard or free/reduced lunch |
| Test Preparation Course | Whether the student completed a test preparation course |
| Math Score | Mathematics exam score |
| Reading Score | Reading exam score |
| Writing Score | Writing exam score |

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Analysis

The project includes:

- Data inspection
- Missing value analysis
- Descriptive statistics
- Correlation analysis
- Probability density and cumulative distribution visualization
- Mathematics score distribution analysis
- Mathematics vs. Reading score relationship
- Effect of parental education on mathematics performance
- Gender-based mathematics score distribution
- Lunch type and mathematics score comparison

---

## Key Findings

- Mathematics, reading, and writing scores are strongly positively correlated.
- Mathematics scores are primarily concentrated between **60 and 80**.
- Students whose parents have higher educational attainment generally achieve slightly higher mathematics scores.
- Male students exhibit a wider distribution of mathematics scores, while female students' scores appear more concentrated around the average.
- Visual exploration alone does not provide sufficient evidence to conclude whether completing the test preparation course significantly affects student performance. Additional statistical testing would be required.

---

## Repository Structure

```
.
├── exams.csv
├── analysis.ipynb
└── README.md
```

---

## Purpose

This repository is preserved as one of my university projects to document my experience with exploratory data analysis and Python-based data visualization.

Although my current professional interests have evolved, I believe it is valuable to keep earlier projects as a record of my learning process and technical development.

---

## License

This project is intended for educational purposes only.

Dataset copyright belongs to its original authors and is available through Kaggle.
