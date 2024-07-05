# Campus Recruitment Prediction


## Project Overview
The placement of students is a crucial objective for educational institutions. It significantly impacts the institution's reputation and yearly admissions. This project aims to predict whether a student will be recruited in campus placements based on various factors in the provided dataset. This assistance will benefit both the students and the institution by enhancing the placement process.

## Dataset
The dataset used for this project is from the Campus Recruitment Prediction course project on Kaggle. It contains various features that describe student demographics, academic performance, and other relevant factors.

## Data Dictionary

sl_no - Serial Number (dropped during preprocessing)

gender - Gender of the student (0 = Male, 1 = Female)

ssc_p - Secondary Education percentage (10th Grade)

ssc_b - Board of Education for 10th Grade (0 = Central, 1 = Others)

hsc_p - Higher Secondary Education percentage (12th Grade)

hsc_b - Board of Education for 12th Grade (0 = Central, 1 = Others)

hsc_s - Specialization in Higher Secondary Education

degree_p - Degree Percentage

degree_t - Type of Undergrad Degree

workex - Work Experience (0 = No, 1 = Yes)

etest_p - E-test Percentage (Engineering Test)

specialisation - Postgrad Specialization

mba_p - MBA Percentage

status - Placement Status (0 = Not Placed, 1 = Placed)

salary - Salary offered (dropped during preprocessing)


## Project Steps
### Data Exploration

- Understand the structure and characteristics of the dataset.
- Identify the types of features and their distributions.

### Data Cleaning

- Handle missing values.
- Correct any inconsistencies in the data.
- Encode categorical variables.

### Feature Engineering

- Create new features if necessary.
- Normalize or scale features as needed.

### Model Building

- Experiment with different machine learning algorithms.
- Split the data into training and testing sets.
- Train the models using the training data.

### Model Testing

- Evaluate the models using the testing data.
- Compare model performances using relevant metrics.

### Machine Learning Models
Various classical machine learning algorithms were tried to find the best fit for this prediction task. The models include:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Voting Classifier (combination of Logistic Regression and SVM)

### Evaluation Metrics
The models were evaluated based on the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score

### Results
The performance of each model was compared, and the best-performing model was selected based on the evaluation metrics. The Random Forest model showed the best overall performance.

### How to Run
Clone this repository.

Ensure you have the necessary libraries installed.

Run the Jupyter notebook assignmnet2.ipynb to reproduce the analysis and results.

### Dependencies
- pandas
- numpy
- matplotlib
- scikit-learn