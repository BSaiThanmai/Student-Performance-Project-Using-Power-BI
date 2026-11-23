# Student-Performance-Project-Using-Power-BI

An interactive **Power BI** dashboard analyzing exam performance across **1,000 student records** in **Math**, **Reading**, and **Writing**, exploring how factors such as test preparation courses, parental level of education, and student demographics relate to academic outcomes.

## 📊 Key Metrics & KPIs
- **Total Students:** 1,000
- **Overall Average Score:** 67.77
- **Average Reading Score:** 69.17
- **Average Writing Score:** 68.05
- **Average Math Score:** 66.09
- **Pass Rate %:** 72.0% (based on an average score threshold of 60+)

## 🔍 Key Insights
- **Test Preparation Impact:** Students who completed the test preparation course scored higher across all three subjects compared to those who did not complete it.
- **Parental Education Trend:** Average student scores trend higher alongside higher levels of parental education, ranging from **High School** (~64) up to **Master's Degree** (~74).
- **Subject Comparison:** Reading and writing averages sit slightly higher than math across the overall cohort.

## 🛠️ Tools & Techniques Used
- **Power BI Desktop** for report design, visual layout, and interactive filtering
- **Power Query Editor** for data type validation, text formatting/cleanup, and adding an index column (`Student ID`)
- **DAX (Data Analysis Expressions)** for custom measures (`Overall Avg Score`, `Pass Rate %`, subject averages) and calculated fields

## 📁 Dataset
- **Source:** [Students Performance in Exams (Kaggle)](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Records:** 1,000 rows, 8 original columns (`gender`, `race/ethnicity`, `parental level of education`, `lunch`, `test preparation course`, `math score`, `reading score`, `writing score`)

## 🖼️ Dashboard Preview
*(Add your screenshot image to the repository—for example, `dashboard-preview.png`—and link it here:)*

```text
![Students Performance Dashboard](dashboard-preview.png)
