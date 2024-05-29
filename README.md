# Tracking User Engagement 

## Project Overview

This project aims to analyze whether the new additions to our platform—such as new courses, exams, and career tracks—have increased student engagement. By leveraging SQL, Excel, and Python, we will examine a dataset from our company's data to draw meaningful insights regarding student engagement metrics.

### Hypothesis

The first half of 2022 was expected to be profitable for the company due to hypothesized increased student engagement following the release of several new features on the company’s website at the end of 2021. These features include enrolling in career tracks and testing knowledge through various exams, as well as an expanded course library.

### Dataset

The dataset includes the following:

1. **Certificates Issued**: Holder (student ID) and issuance date of certificates issued in Q2 2022.
2. **Student Registrations**: Student ID and registration date of students registered between January 1, 2020, and June 30, 2022.
3. **Purchases**: Student ID, product type, purchase date, and refund date (if applicable) of purchases made between January 1, 2020, and June 30, 2022.
4. **Course Watching**: Student ID, time watched, and date of courses watched in Q2 2021 and Q2 2022.

### Tools and Libraries

This project utilizes:

- **SQL**: MySQL Workbench 8.0 or later
- **Excel**: Excel 2007 or later
- **Python**: Python 3 with the following libraries:
  - pandas
  - matplotlib
  - statsmodels
  - scikit-learn
  - seaborn

## Project Workflow

### Part 1: Data Preparation with SQL – Creating a View

In this part, we create a SQL view to aggregate and organize the raw data for easier analysis.

### Part 2: Data Preparation with SQL – Splitting Into Periods

We split the dataset into different periods to facilitate comparison and trend analysis.

### Part 3: Data Preparation with SQL – Certificates Issued

We focus on extracting and preparing data related to certificates issued in Q2 2022.

### Part 4: Data Preprocessing with Python – Removing Outliers

Using Python, we preprocess the data to remove outliers that could skew the analysis.

### Part 5: Data Analysis with Excel – Hypothesis Testing

We use Excel to perform hypothesis testing, determining whether the new features have statistically significantly affected student engagement.

### Part 6: Data Analysis with Excel – Correlation Coefficients

In this step, we calculate correlation coefficients to explore relationships between different engagement metrics.

### Part 7: Dependencies and Probabilities

We analyze dependencies and probabilities to understand the likelihood of various engagement outcomes.

### Part 8: Data Prediction with Python - Creating a Linear Regression

Finally, we build a linear regression model using Python to predict future student engagement based on historical data.

## Conclusion

By following this comprehensive workflow, we aim to provide insights into whether the new platform features have effectively increased student engagement and to identify key drivers of engagement.

## Repository Structure

- **SQL Scripts**: Contains SQL scripts used for data preparation.
- **Excel Files**: Contains Excel files used for hypothesis testing and correlation analysis.
- **Python Scripts**: Contains Python scripts used for data preprocessing, outlier removal, and linear regression modeling.
- **Data**: Contains sample data used in the analysis (if permissible to share).

## How to Run

1. **SQL**: Use MySQL Workbench to execute SQL scripts in the `SQL Scripts` folder.
2. **Excel**: Open the Excel files in the `Excel Files` folder to view and analyze the data.
3. **Python**: Run Python scripts in the `Python Scripts` folder using a Python 3 environment with the required libraries installed.

## Libraries Installation

```sh
pip install pandas matplotlib statsmodels scikit-learn seaborn
```


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
