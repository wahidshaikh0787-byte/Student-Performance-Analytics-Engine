# 🎓 Student Performance Analytics Engine

## 📌 Project Overview

The **Student Performance Analytics Engine** is a Python-based data analysis project that uses NumPy to analyze the academic performance of 500 students across 6 subjects. It calculates statistical measures, detects unusual marks using Z-scores, ranks students, and exports the results to a CSV file.

## 🎯 Objectives

- Generate a 500 × 6 student marks matrix.
- Calculate subject-wise and student-wise statistics.
- Detect outliers using Z-scores and NumPy broadcasting.
- Rank students based on their total marks.
- Combine marks and totals using `numpy.hstack()`.
- Export the final results to CSV.

## 🛠️ Technologies Used

- Python
- NumPy
- Google Colab
- CSV

## ✨ Features

### 1. Marks Matrix Generation
Generate marks for 500 students across 6 subjects using NumPy and a random seed for reproducible results.

### 2. Statistical Analysis
Calculate the following statistical measures:

- Sum
- Mean
- Median
- Standard deviation
- Variance

Use `axis=0` for subject-wise analysis and `axis=1` for student-wise analysis.

### 3. Z-Score and Outlier Detection
Calculate Z-scores using broadcasting to identify marks that are unusually high or low compared with the subject average.

### 4. Student Ranking
Calculate the total marks of each student and rank students from highest to lowest total score.

### 5. CSV Export
Use `numpy.hstack()` to combine the original marks with total marks and export the results as a CSV file.

## 📊 Project Specifications

| Specification | Details |
|---|---|
| Number of students | 500 |
| Number of subjects | 6 |
| Data structure | NumPy array |
| Statistical analysis | Sum, mean, median, standard deviation, variance |
| Outlier detection | Z-score |
| Ranking | Based on total marks |
| Output format | CSV |

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new Python notebook.
3. Import NumPy and generate the marks matrix.
4. Calculate the required statistics.
5. Perform Z-score outlier detection.
6. Calculate total marks and student rankings.
7. Export the results using `numpy.savetxt()` or Pandas.
8. Download the CSV file using `files.download()` in Google Colab.

## 📁 Project Structure

```text
Student-Performance-Analytics-Engine/
│
├── README.md
├── Student_Performance_Analytics.ipynb
└── student_results.csv
```

## 📈 Expected Results

- Subject-wise statistical summaries.
- Student-wise statistical summaries.
- Z-scores and outlier flags.
- Student totals and rankings.
- Downloadable CSV results.

## 📚 Learning Outcomes

- NumPy array creation and manipulation.
- Axis-based statistical calculations.
- Broadcasting and Z-score calculations.
- Outlier detection.
- Sorting and ranking data.
- Exporting data to CSV.

## 👨‍💻 Author

**Wahid Shaikh**

GitHub: [@wahidshaikh0787-byte](https://github.com/wahidshaikh0787-byte)

## ⭐ Conclusion

This project demonstrates how NumPy can be used to perform efficient statistical analysis on student marks, identify outliers, rank academic performance, and export results for further analysis.

---

*Built with Python and NumPy in Google Colab.*
