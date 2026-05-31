# EasyVisa: Robut Data Modeling with Ensembling and Tuning Techniques

## Project Overview
The increasing demand for skilled foreign professionals has led organizations to rely heavily on visa certification processes for international hiring. Evaluating visa applications involves analyzing multiple factors such as education, work, experience, wage levels, employer details, and emplyment conditions. Manual assessment of these applications can be time-consuming and may lead to inconsistencies in decision-making.
This project aims to develop a machine learning-based predictive system that can determine whether a visa application is likely to be Certified or Denied. BY leveraging ensemble learning techniques and hyperparameter tuning, the project focuses on building a robust classification model that ca support faster and more reliable decision making

## Business Problem
The Office of Foreign Labor Certification (OFLC) processes a large number of labor certification applications every year. As the volume of applications increases, manually reviewing each application becomes increasingly challenging.
The objective of this project is to use historical visa application data to:
- Predict visa certification outvomes.
- Identify the factors that influence approval decisions.
- Reduce the time and effort required for manual screening.
- Improve consistency and efficiency in decision-making.

## Dataset Description
The dataset contains 25,480 visa application records and includes information related to applicants, employers, job characteristics, and wage details. Each record represents a visa application, while the target variable indicates whether the application was Certified or Denied.
The dataset includes features such as applicant continent, education level, work experience, training requirements, company size, year of establishment, employment region, prevailing wage, wage unit, and employment type.
This is a binary classification problem where the goal is to predict visa certification status.

## Project Workflow
The project was carried out through the following stages:
1. Exploratory Data Analysis (EDA)
   - Understanding data structure and distributions
   - Identifying outliers and inconsistencies
   - Analyzing relationships between variables.
2. Data Processing
   - Removing irrelevant features
   - Encoding categorical variables
   - Standardizing wage values
   - Handling outliers through transformations
   - Splitting data into training and testing sets
3. Handling Class Imbalance
   - Original Dataset
   - Random Oversampling
   - Random Undersampling
4. Model Development
   - Decision Tree Classifier
   - Random Forest Classifier
   - AdaBoost Classifier
   - Gradient Boosting Classifier
   - XGBoost Classifier
5. Hyperparameter Tuning
   - Optimizing model parameters to improve performance and generalization

## Evaluating Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

## Results
Several machine learning models were trained and compared. While Decision Tree and Random Forest showed signs of overfitting, boosting algorithms demonstrated stronger generalization capabilities.
Among all models, Gradient Boosting emerged as the best-performing model. It achieved the highest testing performance while maintaining a good balance between precision and recall. The model also exhibited minimal overfitting and strong predictive capability on unseen data.

## Key Insights
The analysis revealed several important factors influencing visa approva; decisions:
- Applicants with higher education leve;s tend to have higher certification rates.
- Candidates with prior work experience are more likely to receive visa approval.
- Full-time positions show higher approval rates than part-time positions.
- Wage levels influence certification outcomes.
- Geographic region and applicant origin contribute to prediction performance.
- Combining multiple features significantly improves prediction accuracy.

## Technologies Used
### Programming Language:
- Python
### Libraries:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Imbalanced-Learn
- Joblib
### Development Environment
- Google Colab


## Future Improvements
Potential enhancements for this project include:
- Deploying the model using Streamlit or Flask
- Building an interactive dashboard for predictions.
- Integrating real-time application data.
- Exploring advanced feature engineering techniques.
- Comparing performance with deep learning models.

## Conclusion
This project demonstrates how machine learning and ensemble techniques can be applied to solve a real-world business problem. By analyzing historical visa application data and identifying key approval factors, the developed predictive model can assist organizations in making faster, more consistent, and data-driven hiring decisions.

## Author
Arhana Sen Chowdhury
Chemical Engineering Graduate | PGP in Data Science with Generative AI
 
