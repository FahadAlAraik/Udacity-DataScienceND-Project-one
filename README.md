# IBM Employee Attrition and Job Satisfaction Analysis

Medium Blog-post: https://fahadalaraik.medium.com/decoding-professional-journeys-a-data-driven-exploration-into-employee-dynamics-at-ibm-0fde275a3e6c

![Project Image](https://www.ibm.com/brand/experience-guides/developer/8f4e3cc2b5d52354a6d43c8edba1e3c9/02_8-bar-reverse.svg)

## Introduction

This repository presents the analysis of IBM employee attrition and job satisfaction, conducted as part of the Audacity Data Science Nano Degree. The study aims to answer three key questions:

1. **The Proximity Paradox:** Does the distance (in miles) between an employee’s home and workplace influence job satisfaction?

2. **On the Road to Satisfaction:** Do frequent travelers experience lower job satisfaction?

3. **Relationships Matter?:** Is there a discernible link between attrition rates and an individual’s relationship status?

## Key Findings

In conclusion, the analysis revealed the following insights:

- **Distance from Home and Job Satisfaction:** Contrary to expectations, the distance from home to work doesn’t significantly affect job satisfaction.

- **Travel Frequency and Job Satisfaction:** The study found no clear correlation between travel frequency and job satisfaction among employees.

- **Relationship Status and Attrition:** Marital status emerged as a significant factor in attrition rates. Single employees exhibited the highest attrition rate, with a percentage of 51%.

## Predictive Model Results

A logistic regression model was employed to predict employee attrition. The model's best parameters were found to be:
- **Parameters:** {'C': 1, 'class_weight': None, 'max_iter': 100, 'penalty': 'l2', 'solver': 'liblinear'}

The model demonstrated robust performance with the following metrics:
- **Accuracy:** 87%
- **Precision (Weighted Avg):** 86%
- **Recall (Weighted Avg):** 87%
- **F1 Score:** 92%

## Getting Started

Follow these steps to explore the project and its findings:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/FahadAlAraik/Udacity-DataScienceND-Project-one
   cd Udacity-DataScienceND-Project-one
   ```

2. **Install the Necessary Requirements:**
   ```bash
   pip install pandas numpy scikit-learn scipy matplotlib seaborn
   ```
   

## Project Structure

- `IBM_Attrition_Analysis.ipynb`: Jupyter Notebook containing the code and analysis.
- `HR-Employee-Attrition.csv`: the dataset used in the analysis.
- `ibm-logo-white.PNG`: Directory for storing images and visualizations.
- `README.md`: Detailed information about the project, questions, and findings.

## Acknowledgments

Special thanks to the Audacity Data Science Nano Degree program for providing the opportunity to explore and analyze real-world datasets. The findings and insights generated in this study contribute to the ongoing conversation about employee satisfaction and attrition in the workplace.

Feel free to explore the code, run the notebook, and share your feedback!

---
