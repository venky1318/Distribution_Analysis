# Task 27 — Distribution Analysis Using Python

## Project Overview

This project demonstrates numerical distribution analysis using Python, Pandas, NumPy, and Matplotlib.

A sample student performance dataset containing 30 numerical observations is used to create a histogram and understand the distribution of student marks.

The project also calculates descriptive statistics and analyzes the concentration, spread, and skewness of the data.

## Objectives

- Create a histogram for a numerical variable.
- Understand the frequency distribution of student marks.
- Experiment with different histogram bin sizes.
- Calculate mean, median, and standard deviation.
- Identify minimum, maximum, and range.
- Analyze possible skewness.
- Record at least three observations.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook

## Dataset Description

The project uses a manually created student marks dataset containing 30 fictional student records.

The dataset includes:

- `student_id` — Unique student identifier.
- `marks` — Marks obtained by each student.

The marks range from 35 to 96.

## Visualization

### Histogram of Student Marks

The histogram uses seven bins with intervals of 10 marks to represent the frequency distribution.

It also includes vertical reference lines for the mean and median.

### Histogram Bin Comparison

Additional histograms using five and ten bins demonstrate how the number of bins affects the visual representation of the distribution.

## Statistical Results

| Metric | Value |
|---|---:|
| Number of students | 30 |
| Mean | 67.50 |
| Median | 68.00 |
| Standard deviation | 13.25 |
| Minimum | 35 |
| Maximum | 96 |
| Range | 61 |
| Skewness | -0.289 |

## Key Observations

1. Nineteen students, representing 63.33% of the dataset, scored between 60 and 79.
2. The mean and median are very close, indicating an approximately balanced distribution.
3. The negative skewness value indicates a slight left skew.
4. Marks range from 35 to 96, indicating variation in student performance.

## Project Files

- `Task_27_Distribution_Analysis.ipynb` — Complete Colab notebook.
- `student_marks.csv` — Student marks dataset.
- `distribution_summary.csv` — Statistical summary.
- `marks_frequency_table.csv` — Frequency distribution.
- `requirements.txt` — Required Python libraries.
- `README.md` — Project documentation.
- `project_report.pdf` — Formal project report.
- `charts/marks_distribution_histogram.png` — Main histogram.
- `screenshots/` — Actual notebook execution evidence.

## Conclusion

This project demonstrates how histograms and descriptive statistics can be used to understand numerical data distributions.

The analysis identifies the concentration, spread, and slight negative skewness of student marks, providing practical experience in statistical data analysis and visualization.
