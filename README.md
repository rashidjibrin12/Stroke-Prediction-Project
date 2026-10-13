# Stroke Prediction Project

This project was a personal dive into a real healthcare problem: using patient data to identify factors associated with stroke risk and testing whether a machine learning model could support early intervention. I wanted to move beyond just building a model and instead think through the data story behind it — what patterns matter, what features carry risk, and how a predictive approach could be useful in a clinical or business setting.

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering and encoding
- Handling class imbalance in classification problems
- Model training and evaluation
- Data visualization for insight communication
- Translating technical findings into business-oriented recommendations

## Project Overview

The goal of this project was to build a predictive model that estimates whether a patient is likely to experience a stroke based on demographic and health-related variables. The dataset includes information such as age, gender, work type, smoking status, blood glucose levels, BMI, and medical history indicators like hypertension and heart disease.

I approached the project as a full data science workflow: understanding the data, cleaning inconsistencies, exploring relationships, preparing features, and comparing model performance. The notebook walks through how the data was transformed and how machine learning was used to classify risk.

## Business Questions

This project was designed to answer questions that matter in both healthcare and decision-making contexts:

- Which patient factors are most strongly associated with stroke risk?
- Can demographic and health variables help identify high-risk individuals earlier?
- How useful is a machine learning model when applied to a real-world medical classification problem?
- Which features should be prioritized for intervention, monitoring, or further clinical analysis?

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Machine learning classification workflows

## Dataset

The project uses the publicly available stroke prediction dataset from Kaggle, containing patient records with both clinical and lifestyle attributes. It includes a mix of numerical and categorical variables, with the target variable indicating whether a stroke occurred.

Key features in the dataset include:

- Age
- Gender
- Hypertension
- Heart disease
- Ever married
- Work type
- Residence type
- Average glucose level
- BMI
- Smoking status
- Stroke (target variable)

## Key Insights

A few patterns stood out during the analysis:

- Age appears to be one of the most important drivers of stroke risk.
- Hypertension and heart disease are strong indicators that are worth monitoring closely.
- Elevated glucose levels and lifestyle factors may contribute to a higher likelihood of stroke.
- The dataset is imbalanced, which makes model evaluation more nuanced and reinforces the importance of thoughtful validation.
- Simple but well-structured preprocessing can make a meaningful difference in model quality and interpretability.

These findings are useful because they show the value of combining data exploration with predictive modeling. Rather than treating the model as a black box, the project highlights the real-world drivers behind the risk signal.

## Closing

This project was valuable because it combined technical work with a practical healthcare use case. It strengthened my ability to clean data, build classification models, and communicate findings in a way that connects machine learning to real decisions. I see this as a strong example of how data science can support early risk detection and more informed, preventative care.

