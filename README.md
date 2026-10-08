 Statistics for Machine Learning - Experiment 1

 Exploratory Statistical Analysis of Pima Indians Diabetes Dataset

 Aim
To perform exploratory statistical analysis of the Pima Indians Diabetes Dataset by examining its structure, variable types, data quality, statistical characteristics, and important patterns.

Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

Analysis Performed

1. Dataset shape and structure
2. Column names and data types
3. First five records
4. Statistical summary
5. Mean, median, variance and standard deviation
6. Missing value analysis
7. Zero-value analysis
8. Outlier detection using IQR
9. Histograms
10. Boxplots
11. Diabetes outcome distribution
12. Correlation heatmap
13. Glucose vs BMI scatter plot

 Dataset

Pima Indians Diabetes Dataset.

The dataset contains 768 observations, 8 input attributes and one binary outcome variable.

 Key Observations

- Glucose has a strong relationship with diabetes outcome.
- BMI tends to be higher among diabetic patients.
- Age shows a positive association with diabetes.
- Some medical attributes contain zero values that may represent invalid or missing measurements.
- Outliers are present in variables such as Insulin, BMI, DiabetesPedigreeFunction and Pregnancies.

 How to Run

Install the required libraries:

```bash
pip install pandas matplotlib seaborn
