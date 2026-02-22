# Project Overview

This repository contains exploratory data analysis (EDA), machine learning experiments,
and evaluation results for **CSCI316 – Big Data Mining Techniques (Group Assignment)**.
All experiments were conducted using Jupyter Notebooks and exported to PDF
for final submission. Initially, projects was built in Google Colaboratory, however due to
Account Limit and low training speed, the files are trained in local environment.

> ### **Announcement**
Presentation data is based on prior Google Colaboratory execution, the execution time may differ in local environment

---
Local Environment Information
Environment:
- Python: ```3.9.18```
- PySpark: ```3.5.1```
- OS: ```macOS / Linux```
- Library: on ```requirements.txt```

## 📁 Project Composition

```text
.
├── EDA_images/
│   ├── task1_Outlier_heatmap.png
│   ├── task1_null_value_check.png
│   ├── task1_outlier_visualization.png
│   ├── task1_six_cols_distribution.png
│   ├── task2_correlation.png
│   ├── task2_distribution.png
│   ├── task2_feature_correlation_heatmap.png
│   ├── task2_label_distribution.png
│   └── task2_outliers_log_scaled.png
│
├── PDF_files/                   
│   ├── task_1_EDA.pdf
│   ├── task_1_logistic_regression.pdf
│   ├── task_1_random_forest.pdf
│   ├── task_1_svm.pdf
│   ├── task_2_EDA.pdf
│   ├── task_2_logistic_regression.pdf
│   ├── task_2_random_forest.pdf
│   └── task_2_svm_spark.pdf
│
├── task_1_EDA.ipynb
├── task_1_logistic_regression.ipynb
├── task_1_random_forest.ipynb
├── task_1_svm.ipynb
│
├── task_2_EDA.ipynb
├── task_2_logistic_regression.ipynb
├── task_2_random_forest.ipynb
├── task_2_svm_spark.ipynb
│
├── requirements.txt
│
└── README.md
```

# Dataset Directory Configuration
## Local Environment (MacOS)
```python
## Local ENV (MAC) : 
    - test_path = '/Users/jju/Documents/SIM/Semester 1, 2026/CSCI316 Big Data Mining/       Assignments/Group_Assignment_Database/UNSW_NB15_testing-set.csv'
    - train_path = '/Users/jju/Documents/SIM/Semester 1, 2026/CSCI316 Big Data Mining/Assignments/Group_Assignment_Database/UNSW_NB15_training-set.csv'
```
## Google Colab
```python
    - data_path = '/content/drive/MyDrive/University/CSCI316 - Big Data Mining Techniques/Group Assignment'
```

> - #### Google Colab path is used as a final result
> - #### Local ENV is used to enhance model training speed due to Colab usage limit

# Directory Description

- ### EDA_images
Contains all generated visualizations used for exploratory data analysis, including null value checks, outlier analysis, feature distributions, and correlation heatmaps. has only Exploratory Data Analysis chart images.
- ### PDF_files
PDF exports of each Jupyter Notebook. These files were later converted to PDF for final submission.

- ### task_1_*.ipynb
Notebooks related to Task 1, covering EDA and multiple machine learning models.

- ### task_2_*.ipynb
Notebooks related to Task 2, including PySpark-based SVM implementation.

# ⚙️ Environment Information

- File: ```task_1_*.ipynb/ task_2_*.ipynb```

- Executed in local environment

- OS: macOS

- Python environment: virtual environment (.venv)
    > .venv is not included in submission folder

- Main dependencies include:
        - pandas
        - matplotlib
        - scikit-learn
        - tensorflow
        - pyspark
        - ....... (more classes)

(additional libraries are listed in the notebook)

- Details

    - Tested and executed in the local environment

    - Exported to PDF files for submission

# 📝 Notes

Dataset files are not included in this repository due to size and/or licensing constraints.

Results shown in PDF outputs are generated from the same code contained in the notebooks.