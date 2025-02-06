# Employee Attrition Prediction with Machine Learning

## About the Project

Employee retention is a critical concern for many organizations. High turnover rates can result in substantial costs in terms of recruiting, onboarding, and training new employees. The goal of this project is to use data science and machine learning techniques to predict employee attrition, helping HR teams make data-driven decisions to improve retention strategies and reduce costs.

This project uses real-world HR data to build and evaluate several machine learning models that can predict whether an employee is likely to leave the company based on factors like job satisfaction, job involvement, work-life balance, and more.

---

## Problem Statement

Hiring and retaining employees is an extremely complex task that requires capital, time, and skills. The statistics below highlight the challenge:

- Small business owners spend **40%** of their working hours on tasks that do not generate income, such as hiring.
- Companies spend **15%-20%** of an employee's salary to recruit a new candidate.
- The cost of hiring a new employee averages **$7,645** for small corporations (0-500 employees).
- On average, it takes **52 days** to fill a position.

The HR team provided a dataset with employee attributes such as:
- **Job Involvement**
- **Education**
- **Job Satisfaction**
- **Performance Rating**
- **Relationship Satisfaction**
- **Work-Life Balance**

The task was to build a model that predicts which employees are more likely to quit.

---

## Approach - Project Planning & Aims Grid

### Project Goals
- Develop a machine learning model to predict employee attrition.
- Identify key factors influencing employee turnover.
- Provide actionable insights for HR teams to improve retention strategies.

### Aims Grid

| **Objective**                 | **Approach**                                                     |
|-------------------------------|------------------------------------------------------------------|
| **Data Collection**            | Gather and clean HR dataset containing employee attributes.     |
| **Model Development**          | Train various machine learning models: Logistic Regression, Random Forest, and Deep Learning. |
| **Analysis**                   | Analyze patterns in employee attrition data.                    |
| **Results & Recommendations**  | Provide results, model accuracy, and retention recommendations. |

---

## Technologies Used

This project utilizes the following Python libraries:

- **pandas**: For data manipulation and preprocessing.
- **numpy**: For numerical computations.
- **seaborn**: For data visualization and heatmaps.
- **TensorFlow**: For building and training deep learning models.
- **matplotlib**: For generating plots and graphs.

## Results & Findings
Key Takeaways:
Logistic Regression Classifier performed the best with 89.57% accuracy.
Random Forest Classifier showed a good performance with 85.49% accuracy.
Deep Learning Model had an accuracy of 85%, performing slightly worse than the traditional models.

![image alt](https://github.com/MuhammadEmaaz/Employee-Attrition-Prediction-with-Machine-Learning/blob/main/results/1.%20Features%20Histogram.png?raw=true)

![image alt](https://github.com/MuhammadEmaaz/Employee-Attrition-Prediction-with-Machine-Learning/blob/main/results/3.%20Age%20vs%20Attrition.png?raw=true)

![image alt](https://github.com/MuhammadEmaaz/Employee-Attrition-Prediction-with-Machine-Learning/blob/main/results/4.%20Multiple%20Features%20Analysis.png?raw=true)

## Trends Analysis:
Employees aged 29-31 have a higher turnover rate, suggesting career exploration or dissatisfaction.
Single employees are more likely to resign than married or divorced employees.
Roles like Sales Rep, Sales Executive, and Laboratory Technician exhibit higher turnover, possibly due to lower salary expectations.
Employees with Job Involvement level 3 tend to leave more often, indicating potential disengagement.
Employees with 1-2 years of experience at the company are more likely to resign, reflecting early-stage career movements.

## Proposed Next Steps:
Integrating this model into an HR Dashboard for real-time employee retention monitoring.
Further refining the model by including additional features such as benefits, work environment factors, etc.


