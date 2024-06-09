# Analysis-Report-on-Employee-Attrition

# Employee Attrition Analysis

This project analyzes the factors contributing to employee attrition using a dataset from Kaggle. By understanding these factors, we can generate actionable insights to help reduce attrition and improve employee retention strategies.

## Project Overview

Employee attrition, or turnover, can significantly impact a company, resulting in the loss of talent and knowledge, increased recruitment and training costs, workflow disruptions, and negative effects on team morale and productivity. This analysis addresses the following key questions:

1. How does the distance from home affect attrition across different job roles?
2. What is the relationship between job satisfaction and attrition?
3. Is there a significant difference in average monthly income by education level and attrition status?
4. How does work-life balance affect employee attrition?

## Methodology

The analysis follows the OSEMN framework: Obtain, Scrub, Explore, Model, and interpret.

### Obtain

The dataset is sourced from Kaggle and loaded into a pandas DataFrame. It contains 35 columns (variables) and 1470 observations (rows). However, not all features were used in the analysis. The focus was on the features relevant to the specific questions addressed.

### Scrub

Data cleaning steps include:
- Removing duplicate entries
- Handling missing values
- Correcting inconsistent data types
- Dropping columns with no variance

### Explore

Exploratory Data Analysis (EDA) involves:
- Correlation analysis to understand relationships between relevant features
- Visualizations like bar plots, box plots, and pair plots to explore the distribution of categorical and numerical features
- Detailed statistical tests such as chi-square tests for categorical variables and t-tests for numerical variables

### Model

Multiple modeling techniques are employed to predict employee attrition:
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- Gradient Boosting Classifier
- K-Nearest Neighbors (KNN)

Model performance is evaluated using classification reports and accuracy scores. Feature importance is also analyzed for models like Random Forest.

### iNterpret

The analysis provides insights and recommendations based on the findings:
- Addressing commute issues by implementing flexible work arrangements
- Enhancing job satisfaction through professional development opportunities and recognition programs
- Offering competitive compensation packages and career development paths
- Promoting work-life balance with flexible working hours and wellness programs

## Usage

To run this analysis:
1. Clone this repository.
2. Ensure you have the necessary libraries installed. You can install them using:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter Notebook `Employee Attrition.ipynb`.

## Conclusion

Organizations can reduce turnover, retain valuable talent, and improve employee satisfaction and productivity by addressing the identified factors contributing to employee attrition.

## Repository Structure

├── data
│ └── Employee_Attrition.csv
├── Employee Attrition.ipynb
├── README.md
└── requirements.txt

## License

This project is licensed under the MIT License.
Database: Open Database, Contents: Database Contents

## Acknowledgments

- Kaggle for providing the dataset.
- Open-source libraries: pandas, numpy, matplotlib, seaborn, scikit-learn.
