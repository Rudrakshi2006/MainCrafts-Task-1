# Student Performance Analysis

## Project Overview
This project analyzes student academic performance using Python data analysis libraries. The analysis is performed on the `student-mat.csv` dataset, which contains information about students enrolled in a Mathematics course.

The objective of this project is to:
- Explore and clean the dataset
- Perform basic statistical analysis
- Identify factors affecting student performance
- Visualize important insights using charts and graphs

---

## Tools & Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

student-performance-analysis/
│
├── data/
│ └── student-mat.csv
│
├── notebooks/
│ └── student_analysis.ipynb
│
└── README.md

---

## Dataset Information
The dataset contains student-related information such as:
- Gender
- Study time
- Family background
- Absences
- Final grades

Target variable:
- `G3` → Final grade of the student

---

## Analysis Performed
The project includes:
- Missing value analysis
- Duplicate record removal
- Dataset structure inspection
- Average final grade calculation
- Performance analysis based on study time
- Gender-wise performance comparison

---

## Visualizations
The following visualizations are included:
- Histogram of final grades
- Scatterplot of study time vs grades
- Bar chart comparing male and female average scores

---

## How to Run the Project

1. Clone or download the project folder
2. Install required libraries:

```bash
pip install pandas matplotlib seaborn