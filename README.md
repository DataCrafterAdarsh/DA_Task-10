====================================================
        TASK 10 : PYTHON EDA ANALYSIS
====================================================

PROJECT TITLE
----------------------------------------------------
Python EDA – Student Performance Dataset


OBJECTIVE
----------------------------------------------------
To perform Exploratory Data Analysis (EDA) on the
Student Performance dataset and detect and handle
outliers using the IQR method.


DATASET
----------------------------------------------------
Name : Student Performance Dataset

Description :
The dataset contains academic, demographic, and
social attributes of students such as study time,
family background, absences, and exam scores
(G1, G2, G3).


TOOLS & LIBRARIES
----------------------------------------------------
• Platform : Google Colab / Jupyter Notebook
• Language : Python
• Libraries :
  - pandas
  - numpy
  - matplotlib


STEPS PERFORMED
----------------------------------------------------
1. Loaded the dataset and checked shape, head,
   and data types.
2. Generated descriptive statistics for numerical
   columns.
3. Checked missing value percentage (no missing
   values found).
4. Plotted histograms and boxplots to understand
   data distribution.
5. Detected outliers using the IQR method.
6. Created an outlier flag column.
7. Handled outliers using capping instead of
   removing records.
8. Created correlation matrix for numerical
   features.
9. Exported the cleaned dataset.


OUTLIER HANDLING
----------------------------------------------------
• Method Used : IQR (Interquartile Range)
• Column Focused : Absences
• Technique Applied : Capping
• Reason :
  Absences may contain valid extreme values,
  so capping preserves useful data.


KEY INSIGHTS
----------------------------------------------------
• Strong positive correlation between G1, G2,
  and G3.
• Study time has a positive impact on grades.
• Number of failures negatively affects final
  performance.
• Absences show right-skewed distribution with
  outliers.


DELIVERABLES
----------------------------------------------------
• task10_eda.ipynb
• cleaned_student_performance.csv
• eda_findings.txt


FINAL OUTCOME
----------------------------------------------------
• Practical experience with EDA
• Clear understanding of outlier detection
• Improved data interpretation skills


AUTHOR
----------------------------------------------------
Adarsh Mishra
====================================================
