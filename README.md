# Predictive Analysis of Mental Health Trends in the Tech Industry

## Project Overview
This project leverages machine learning to analyze data from the Open-Source Mental Illness (OSMI) survey, focusing on predicting mental health outcomes within the tech industry. By utilizing XGBoost, the most accurate predictive model, and LIME (Local Interpretable Model-agnostic Explanations) for interpretability, the project identifies key factors influencing mental health issues. The insights derived aim to help organizations implement targeted interventions to create healthier workplace environments.

## Key Objectives
1. **Predict Mental Health Outcomes**: Use machine learning to predict the likelihood of mental health issues among tech industry employees.

2. **Identify Key Drivers**: Uncover the most significant factors contributing to mental health challenges.

3. **Provide Actionable Insights**: Offer data-driven recommendations for organizations to improve employee well-being.

## Methodology
1. *Data Collection and Preprocessing*:
     * Collected data from the OSMI survey, which includes responses on mental health, workplace environment, and demographics.
     * Cleaned and preprocessed the data to handle missing values, outliers, and categorical variables.
2. *Exploratory Data Analysis (EDA)*:
    * Conducted univariate and multivariate analysis to understand data distributions and relationships.
    * Visualized trends and patterns using Power BI and Python libraries like Matplotlib and Seaborn.
3. *Feature Engineering*:
     * Applied K-means clustering to group similar data points and identify patterns.
     * Used Label Encoding to convert categorical variables into numerical formats for model training.
4. *Model Training and Prediction*:
    * Trained multiple machine learning models, including XGBoost, Random Forest, and Logistic Regression.
    * Selected XGBoost as the best-performing model based on accuracy and F1-score.
5. *Model Evaluation*:
    * Evaluated model performance using metrics like accuracy, precision, recall, and ROC-AUC.
    * Conducted cross-validation to ensure robustness.
6. *Explainable AI with LIME*:
    * Used LIME to interpret the XGBoost model's predictions and identify the most influential features driving mental health outcomes.

## Tools and Technologies
* Programming Language: Python
* Machine Learning Libraries: Scikit-learn, XGBoost
* Explainable AI: LIME
* Data Visualization: Power BI, Matplotlib, Seaborn
* Data Preprocessing: Pandas, NumPy

## Results
1. Improved Model Accuracy:
   * Achieved high accuracy in predicting mental health outcomes using XGBoost.
   * Outperformed baseline models like Logistic Regression and Random Forest.
2. Key Insights:
   * Identified factors such as workplace support, job role, work hours, and company size as significant predictors of mental health issues.
   * Found that employees in smaller companies or those with limited mental health resources are at higher risk.
3. Actionable Recommendations:
   * Organizations should prioritize mental health resources, especially for smaller companies.
   * Implement policies to reduce overwork and promote work-life balance.
   * Foster a supportive workplace culture to mitigate mental health risks.

## Visualizations
1. Basic Data Visualization:
   * Visualized survey responses to understand trends in mental health, workplace environment, and demographics.
![image](https://github.com/user-attachments/assets/16e61313-48fb-49d3-b8fc-5cd74af4ede7)
![image](https://github.com/user-attachments/assets/960575f3-da21-4604-a390-0658c1d62e72)
![image](https://github.com/user-attachments/assets/69035d21-497b-4582-97d2-fdf954370d52)
![image](https://github.com/user-attachments/assets/7917b5b0-59e2-44de-a394-fdb978cf5424)
![image](https://github.com/user-attachments/assets/df1777de-de60-4455-a41e-994663d4c1b6)


2. **XGBoost with LIME**:
  * Used LIME to explain individual predictions, highlighting the contribution of each feature.
![image](https://github.com/meggie2002/Predictive-Mental-Health-Analysis/assets/171136650/f1678ca5-0904-45f0-87da-be462bc34b0b)
  * Visualized feature importance and local interpretability for actionable insights.
![image](https://github.com/meggie2002/Predictive-Mental-Health-Analysis/assets/171136650/51e91238-bc8b-494e-8806-f9d6c6712b16)

## Conclusion
This project demonstrates the power of machine learning in understanding and predicting mental health trends in the tech industry. By combining XGBoost for accurate predictions and LIME for interpretability, the project provides actionable insights that can help organizations create healthier and more supportive workplace environments. The findings underscore the importance of addressing mental health proactively, especially in high-pressure industries like tech.
