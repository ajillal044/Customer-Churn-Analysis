# UNDERSTANDING CUSTOMER CHURN: INSIGHTS FROM TED TED & AND POPPY PET SHOP

![Image](https://github.com/user-attachments/assets/b4fbb99d-6432-4bd5-abd0-fdf7fe80d77d)

## Project Overview

This project is focused on understanding customer churn at Ted and Poppy Pet Shop using advanced machine learning models. The analysis aimed to identify key factors influencing customer retention and to develop actionable strategies for improving customer loyalty. The project leveraged various machine learning algorithms to predict customer churn effectively.


## Project Goals

* To identify the key drivers of customer churn at Ted and Poppy Pet Shop.
* To apply advanced machine learning models to predict customer churn.
* To provide actionable recommendations to enhance customer retention.

## Data Description

* **Dataset:** Synthetic customer data from Ted and Poppy Pet Shop.
* **Total Records:** 200,000
* **Key Variables:** Age, Days Since Last Web Purchase, Satisfaction Survey, Average Purchase Value, Payment Issue.

## Methods and Techniques

* Data Cleaning: Removed foreign characters and handled missing values.
* Feature Engineering: Created active engagement features.
* Data Splitting: 70% training data and 30% testing data.
* Classification Models: Applied three machine learning models:

  * LightGBM
  * Random Forest
  * XGBoost
* Model Evaluation Metrics:

  * Accuracy
  * Sensitivity
  * Area Under Curve (AUC)

## Model Performance

| Model         | Accuracy | Sensitivity | AUC   |
| ------------- | -------- | ----------- | ----- |
| LightGBM      | 0.752    | 0.74        | 0.741 |
| Random Forest | 0.744    | 0.728       | 0.732 |
| XGBoost       | 0.816    | 0.824       | 0.81  |

## Key Insights

* Payment issues are a significant driver of churn.
* Churn rate increases with age.
* Customers with lower satisfaction scores are more likely to churn.
* High-value customers are more likely to be retained.

## Recommendations

* Proactively resolve payment issues, especially for older customers.
* Use customer satisfaction surveys to improve services.
* Implement loyalty programs to retain high-value customers.

## Usage Instructions

* Ensure R and RStudio are installed.
* Load the project files in RStudio.
* Run the R script for data preprocessing, model training, and evaluation.

## Acknowledgments

We would like to thank the University of Auckland for providing the resources and guidance for this project.

## License

This project is for educational purposes and is not for commercial use.
