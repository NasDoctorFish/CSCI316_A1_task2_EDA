# Project Composition
.
├── EDA_images
│   ├── task1_Outlier_heatmap.png
│   ├── task1_null_value_check.png
│   ├── task1_outlier_visualization.png
│   ├── task1_six_cols_distribution.png
│   ├── task2_correlation.png
│   ├── task2_distribution.png
│   ├── task2_feature_correlation_heatmap.png
│   ├── task2_label_distribution.png
│   └── task2_outliers_log_scaled.png
├── HTML(later to PDF)
│   ├── task_1_EDA.html
│   ├── task_1_logistic_regression.html
│   ├── task_1_random_forest.html
│   ├── task_1_svm.html
│   ├── task_2_EDA.html
│   ├── task_2_logistic_regression.html
│   ├── task_2_random_forest.html
│   └── task_2_svm_spark.html
├── README.md
├── task_1_EDA.ipynb
├── task_1_logistic_regression.ipynb
├── task_1_random_forest.ipynb
├── task_1_svm.ipynb
├── task_2_EDA.ipynb
├── task_2_logistic_regression.ipynb
├── task_2_random_forest.ipynb
└── task_2_svm_spark.ipynb

# DB Directory
Local ENV (MAC) : 
    # test_path = '/Users/jju/Documents/SIM/Semester 1, 2026/CSCI316 Big Data Mining/Assignments/Group_Assignment_Database/UNSW_NB15_testing-set.csv'
    # train_path = '/Users/jju/Documents/SIM/Semester 1, 2026/CSCI316 Big Data Mining/Assignments/Group_Assignment_Database/UNSW_NB15_training-set.csv'

Google Colab : '/content/drive/MyDrive/University/CSCI316 - Big Data Mining Techniques/Group Assignment'

# Environment Info
task_1_EDA.ipynb 
- Local Environment (MacOS with python virtual env)
- Requirements
    - matplotlib, pandas, tensorflow, pyspark, scikit-learn
    - ...
Other jupiter notebook
- Tested and pdf generated on Local ENV
- Directory changed into Colab Directory

# Directory Description

- EDA_images/
Contains all generated visualizations used for exploratory data analysis, including null value checks, outlier analysis, feature distributions, and correlation heatmaps.

- HTML/
HTML exports of each Jupyter Notebook. These files were later converted to PDF for final submission.

- task_1_*.ipynb
Notebooks related to Task 1, covering EDA and multiple machine learning models.

- task_2_*.ipynb
Notebooks related to Task 2, including PySpark-based SVM implementation.

# ⚙️ Environment Information
Task 1 – EDA Notebook

- File: task_1_EDA.ipynb

- Executed in local environment

- OS: macOS

- Python environment: virtual environment (venv)

- Main dependencies include:
        - pandas
        - matplotlib
        - scikit-learn
        - tensorflow
        - pyspark
        - ....... (more classes)

(additional libraries are listed in the notebook)

# Other Jupyter Notebooks

All remaining notebooks were:

Tested and executed in the local environment

Exported to HTML

Converted to PDF for submission

During execution, directory paths were adjusted when running in Google Colab to ensure compatibility with Colab’s file system.

# 📝 Notes

Dataset files are not included in this repository due to size and/or licensing constraints.

Results shown in HTML/PDF outputs are generated from the same code contained in the notebooks.

Minor path adjustments may be required depending on the execution environment (local vs Colab).