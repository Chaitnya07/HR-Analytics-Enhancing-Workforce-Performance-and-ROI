# HR Analytics Project: Employee Attrition Analysis
<div align="center">
  <a href="#">
    <img src="https://www.ismartrecruit.com/upload/blog/main_image/banner-image.webp">
  </a>
</div>

<br>

This project focuses on **HR Analytics** with an emphasis on analyzing and predicting **employee attrition**. Through data-driven techniques, this project aims to provide insights into the impact of employee attrition on companies and how HR Analytics can help mitigate its negative effects.

## Table of Contents
1. [Project Overview](#project-overview)
2. [What is HR Analytics?](#what-is-hr-analytics)
3. [Attrition in HR](#attrition-in-hr)
4. [Impact of Attrition on Companies](#impact-of-attrition-on-companies)
5. [Dataset](#dataset)
6. [Modeling and Predictions](#modeling-and-predictions)
7. [Key Insights](#key-insights)
8. [Analysis and Visualization](#analysis-and-visualization)
9. [Contact](#contact)

## Project Overview

In today’s competitive world, companies invest significant resources in hiring, training, and developing their employees. However, **employee attrition** poses a challenge, leading to increased costs and reduced organizational efficiency. This project demonstrates how **HR Analytics** can be used to predict employee attrition and improve retention strategies.

## What is HR Analytics?

**HR Analytics** is the application of analytical processes to the human resources function within an organization. The goal is to improve employee performance and optimize operational efficiency, ultimately increasing the return on investment (ROI). **HR Analytics** provides insights into how various HR processes can be improved to better retain employees.

## Attrition in HR

**Attrition** refers to the gradual loss of employees over time. High attrition rates are problematic for companies as they increase hiring and training costs and reduce the organization’s collective knowledge base. **HR professionals** often design compensation programs and work culture initiatives to retain top talent.

## Impact of Attrition on Companies

High employee attrition can severely impact an organization:
- **Increased Costs**: Companies face high expenses in hiring, training, and onboarding new employees.
- **Reduced Knowledge Base**: Employee turnover can lead to the loss of experience and expertise within the organization.
- **Customer Impact**: In customer-facing roles, frequent turnover can negatively affect customer satisfaction and loyalty.

## Dataset

For this project, we will use the **IBM HR Analytics dataset**, which contains various employee attributes such as job satisfaction, work-life balance, salary levels, and more. These factors will be explored to predict attrition and provide insights into retention strategies.

You can access the dataset [here](https://github.com/dsrscientist/IBM_HR_Attrition_Rate_Analytics).

### Data Loading and Preprocessing

```python
import pandas as pd
data = pd.read_csv('hr.csv')
data.head()
```


## Modeling and Predictions

Several machine learning models were used to predict employee attrition, including:

1. Random Forest Classifier
2. K-Neighbors Classifier
3. Ensemble Boosting Techniques

After hyperparameter tuning with Grid Search CV, the Random Forest Classifier achieved the best performance with an accuracy of 85% and cross-validation score of 83%.

## Key Insights

1. **Attrition Patterns**: The analysis identifies key factors such as job satisfaction, salary, and work-life balance that drive employee turnover, enabling companies to implement strategies to reduce attrition.

2. **Cost of Attrition**: High turnover raises hiring and training expenses, making it difficult for companies to retain knowledge and sustain customer relationships.

3. **Predictive Modeling**: The project employs machine learning models like **Random Forest** and **K-Neighbors Classifier** to predict attrition with up to **85% accuracy**, providing actionable insights for enhancing employee retention.

## Analysis and Visualization

1. **Data Exploration and Visualization**: The project analyzes key features such as age, salary, job role, and satisfaction levels using visualizations like bar plots and histograms to compare employees who left the company (attrition) with those who stayed.

2. **Predictive Modeling**: Machine learning models, including **Random Forest** and **K-Neighbors Classifier**, were trained to predict employee attrition. After tuning with **GridSearchCV**, the Random Forest Classifier achieved the highest accuracy at **85%**.

3. **Comparative Visual Insights**: Dist plots were utilized to compare model performance, illustrating the impact of various features on attrition and helping identify trends for companies to address in order to reduce turnover.

## Contact

For any questions or contributions, feel free to reach out:

- **Email**: chaitnya0709@gmail.com
- **GitHub**: [Chaitnya07](https://github.com/Chaitnya07)
