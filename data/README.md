# 📁 Data Folder

This folder contains the dataset used in the **Student Depression Data Mining Project**. The data was sourced as part of a university data mining assignment and focuses on identifying depression levels among university students based on a variety of personal, academic, and social factors.

## 📄 File

- `student_depression_dataset.csv`: The main dataset used throughout the project, containing anonymized responses from students.

## 🌐 Data Source

The dataset is originally derived from a publicly shared resource on student mental health and has been cleaned and discretized as part of this project. It includes both categorical and numerical features.

> Note: This dataset has been processed for academic purposes and may not be suitable for clinical or diagnostic use.

## 📊 Variable Descriptions

| Variable Name         | Description                                                      | Type          |
|-----------------------|------------------------------------------------------------------|---------------|
| `Gender`              | Gender of the respondent (Female/Male)                           | Categorical   |
| `Age`                 | Age in years                                                     | Numeric       |
| `Course`              | Type of degree program                                           | Categorical   |
| `Year_of_Study`       | Academic year (1st, 2nd, etc.)                                   | Ordinal       |
| `Sleep_Duration`      | Average hours of sleep per night                                 | Numeric       |
| `Stress_Level`        | Self-reported stress level (Low/Medium/High)                     | Categorical   |
| `Social_Support`      | Availability of emotional/social support                         | Categorical   |
| `Depression`          | Binary indicator of depression status (Yes/No)                   | Target        |
| ...                   | *(+ more features used in clustering and modeling)*              | Mixed         |

## 📌 Notes

- The dataset has **9620 rows** and **27 variables** after preprocessing.
- All missing values and inconsistencies have been addressed in the preprocessing scripts.
- The working subset for this project focuses **only on female students**, as filtered in the second phase of the analysis.

## 📁 Related Files

- See `notebooks/PRA1.Rmd` for the initial data exploration and preprocessing.
- See `notebooks/PRA2.Rmd` for modeling and evaluation.

---
