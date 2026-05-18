# MIS-311
Part 1: Data Analysis and Insight
# MIS 311 - Introduction to Business Analytics

## Part 1: Data Analysis and Insight

### 1. Data Overview
[cite_start]The Student Exam Performance dataset used for this exploratory analysis is sourced from internal data within the EIU’s Enterprise System (ERP).

* [cite_start]**Number of Rows:** 10,000 observations 
* [cite_start]**Number of Columns:** 23 variables 
* [cite_start]**Veracity:** Structured data 

**Key Variables Included:**
- [cite_start]`study_hours_per_day`: Average daily study time.
- [cite_start]`attendance_rate`: Percentage of class attendance.
- [cite_start]`social_media_hours`: Average daily time spent on social media.
- [cite_start]`final_exam_score`: Score achieved in the final exam.

### 2. Data Cleaning
[cite_start]Before conducting the analysis, the dataset was rigorously inspected to ensure high data quality:
* [cite_start]**Duplicate Records:** Confirmed 0 duplicate rows, ensuring each observation is unique.
* [cite_start]**Missing Values:** Identified 0 missing values across all 23 columns.
* [cite_start]**Outcome:** The dataset remained consistent at 10,000 rows, perfectly prepared for descriptive statistical analysis.

### 3. Descriptive Statistics
[cite_start]The following table summarizes the central tendency and dispersion of key academic factors:

| Statistic | Study Hours | Attendance Rate | Social Media Hours | Final Exam Score |
| :--- | :--- | :--- | :--- | :--- |
| **Mean** | 3.02 | 84.70% | 2.52 | 49.68 |
| **Median** | 3.01 | 85.10% | 2.50 | 49.55 |
| **Std. Deviation** | 1.18 | 9.51 | 1.45 | 12.15 |
| **Range** | 6.74 | 49.20 | 8.00 | 93.40 |

### 4. Visualizations & Insights

#### Insight 1: Strong Positive Correlation between Study Hours and Academic Results
<img width="312" height="159" alt="Ảnh màn hình 2026-05-18 lúc 19 27 50" src="https://github.com/user-attachments/assets/3fdcfbf8-1e14-450f-8349-e0ac91eec206" />


[cite_start]**Analysis:** Analysis of the scatter plot reveals a clear positive correlation between daily study duration and final exam scores. [cite_start]While the average study time is 3.02 hours, students who maintain sessions of 5 hours or more frequently achieve significantly higher scores. [cite_start]This proves that targeted study effort is a crucial factor in improving grades.

#### Insight 2: Impact of Excessive Social Media Usage on Performance
<img width="322" height="171" alt="Ảnh màn hình 2026-05-18 lúc 19 30 48" src="https://github.com/user-attachments/assets/b9004c07-1469-47e7-b441-3e3ede03397d" />


[cite_start]**Analysis:** The data shows a notable trend regarding social media consumption. [cite_start]While the average usage is 2.52 hours, a sharp decline in academic performance is observed when daily usage exceeds the 4-hour threshold. [cite_start]This suggests that excessive social media acts as a major distractor, and effective screen-time management is essential for academic success.

---
*This portfolio is part of the MIS 311 course requirements at Eastern International University.*
