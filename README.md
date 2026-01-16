COVID-19 Data Preprocessing (Country-wise)

Course: Programming for AI (PFAI)
Assignment: Data Preprocessing and Exploratory Analysis

Introduction

This project focuses on data preprocessing using a COVID-19 country-wise dataset.
The main purpose of this assignment is to understand how raw data is cleaned and
prepared before applying artificial intelligence or machine learning models.

Real-world datasets are often not ready for direct use in AI systems.
Therefore, data preprocessing is a crucial step in the AI pipeline.
This project demonstrates different preprocessing techniques using Python
and Google Colab.

Why COVID-19 Dataset?

The COVID-19 dataset contains country-wise information about confirmed cases,
deaths, recoveries, and weekly changes. This dataset represents real-world
health-related data and helps understand how AI can be applied in the medical
and public health domain.

I selected this dataset because:

- It contains real-world COVID-19 statistics
- It includes both numerical and categorical data
- It is suitable for learning AI preprocessing techniques
- It helps understand data preparation for AI models

What is Data Preprocessing?

Data preprocessing is the process of converting raw data into a clean
and usable format. Raw data may contain text values, different scales,
and inconsistent formats.

Data preprocessing helps to:
- Convert text data into numerical form
- Normalize numerical features
- Improve the performance of AI models

Preprocessing Steps Implemented

1. Loading the Dataset  
The COVID-19 dataset was loaded using the pandas library.

2. Understanding the Dataset  
Basic functions such as info() and describe() were used to analyze
data types, structure, and statistics.

3. Text Cleaning  
Text columns such as Country/Region and WHO Region were cleaned by
converting them to lowercase and removing special characters.

4. Encoding Categorical Data  
Categorical text values were converted into numerical form using
Label Encoding.

5. Feature Scaling  
Numerical features were scaled between 0 and 1 using Min-Max Scaling.
This ensures that all features contribute equally to AI models.

6. Data Visualization  
A histogram was created to visualize the distribution of confirmed
COVID-19 cases.

7. Saving Cleaned Dataset  
The final cleaned dataset was saved as a CSV file for future use
in AI and machine learning models.

Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

How to Run This Project

Step 1: Open Google Colab  
Visit https://colab.research.google.com

Step 2: Upload Files  
Upload the notebook file and the country-wise COVID-19 dataset CSV file.

Step 3: Run the Notebook  
Run each code cell step by step to observe outputs.

Step 4: Check Outputs  
All generated files and graphs are saved inside the outputs folder.

Project Structure

covid19-data-preprocessing-pfai/
│
├── covid19_preprocessing.ipynb
├── country_wise_latest.csv
├── outputs/
│   ├── cleaned_covid_data.csv
│   └── confirmed_cases_distribution.png
└── README.md

Dataset Source

The COVID-19 dataset was obtained from a publicly available source (Kaggle).
It was used strictly for academic and learning purposes.

Conclusion

This project helped me understand the importance of data preprocessing in AI.
I learned how to clean, encode, scale, and visualize real-world data.
These preprocessing steps make the dataset suitable for AI models.

Final Note

This assignment was completed as part of the Programming for AI (PFAI) course.
All work in this repository is original and created for academic learning.
