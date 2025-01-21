### Capstone Project - Heart Disease Prediction

**Author** - Deepika Makkar

#### Executive summary

The project aims to leverage machine learning models to predict the likelihood of heart disease based on patient health indicators, using the publicly available dataset. Early and accurate detection can significantly enhance preventive care and reduce the global burden of heart disease.

#### Rationale
Heart disease leads to premature loss of life and deeply impacts families worldwide. Early prediction of heart disease can encourage healthier lifestyles and save lives. This project focuses on developing an efficient method to detect heart disease using machine learning models.

#### Research Question
Can we accurately predict the likelihood of heart disease in individuals using key health indicators and demographic information?

#### Data Sources
The data for this project will be sourced from the Heart Disease Prediction Dataset on Kaggle, which contains clinical data related to cardiovascular health factors.

#### Methodology
##### Data Preprocessing:
- Cleaning and handling missing values.
- Scaling numerical features and encoding categorical variables.
  
##### Exploratory Data Analysis (EDA):
- Analyzing feature importance and correlation with the target variable.
- Identifying key risk factors associated with heart disease.

##### Model Development and Evaluation:
- Implementing various machine learning models, including Logistic Regression, Decision Trees, Random Forest, Support Vector Machines (SVM), and Gradient Boosting.
- Splitting data into training and testing sets for unbiased model evaluation.
- Hyperparameter tuning to optimize model performance.

##### Evaluation Metrics:
- Assessing models using accuracy, precision, recall, F1-score, and area under the ROC curve (AUC-ROC) to ensure a balanced evaluation.

#### Results
- Certain features, such as cholesterol levels, resting blood pressure, and exercise-induced angina, showed strong correlations with heart disease.
- Ensemble models like Random Forest and Gradient Boosting outperformed others in terms of predictive accuracy and robustness.

#### Next steps
What suggestions do you have for next steps?

#### Outline of project

- [DataOverview Notebook](https://github.com/deepikamakkar/ComparingClassifiers/blob/main/notebooks/DataOverview.ipynb)
- [DataPreprocessing Notebook](https://github.com/deepikamakkar/CapstoneProject/blob/main/notebooks/DataPreProcessing.ipynb)
- [DataModellingMetrics Notebook]()


##### Contact and Further Information
For inquiries, please contact Deepika Makkar at makkar.deepika@gmail.com.
