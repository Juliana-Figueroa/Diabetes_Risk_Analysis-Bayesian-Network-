# Diabetes_Risk_Analysis-Bayesian-Network-

## Project Overview Video

https://www.loom.com/share/bf44072c09e5420995f45a4c0e687957

📌 Project Overview

This project explores diabetes risk prediction using Exploratory Data Analysis (EDA) and Bayesian Networks. The goal was to analyze relationships between demographic, lifestyle, and medical risk factors and estimate the probability of diabetes under different patient conditions.

The project combines statistical visualization, probabilistic modeling, Bayesian inference, and classification evaluation to better understand how multiple health conditions interact to influence diabetes risk.

🎯 Objectives

Explore relationships between medical risk factors and diabetes.
Identify variables most associated with diabetes diagnosis.
Build a Bayesian Network to model probabilistic relationships.
Perform inference to estimate diabetes probability under different scenarios.
Evaluate Bayesian Network classification performance.
Discuss limitations and ethical concerns in medical AI systems.

🛠️ Tools & Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

pgmpy

NetworkX

📂 Dataset Features

The dataset included:

Gender.
Age.
Hypertension.
Heart Disease.
Smoking History.
BMI.
HbA1c Level.
Blood Glucose Level.
Diabetes Diagnosis.

🔍 Exploratory Data Analysis

The EDA focused on identifying patterns between health conditions and diabetes risk using:

Histograms.
Boxplots.
Scatterplots.
Heatmaps.
Countplots.
Correlation analysis.
Multivariate visualizations.

Key analyses included:

Hypertension and heart disease vs diabetes prevalence.
HbA1c and blood glucose relationships.
Age and BMI influence on diabetes risk.
Combined risk factor analysis.

⚙️ Data Preprocessing

Preprocessing steps included:

Duplicate removal

Categorical variable encoding

Discretization of continuous variables into medically meaningful categories

Continuous variables such as:

Age,
BMI,
HbA1c,
Blood glucose,

were discretized to improve Bayesian Network probability estimation and interpretability.

🧠 Bayesian Network Construction

The Bayesian Network modeled relationships between:

Age group,
BMI category,
Hypertension,
Heart disease,
HbA1c category,
Glucose category,
Diabetes diagnosis

The network structure was visualized using NetworkX and parameterized using Maximum Likelihood Estimation.

🔮 Bayesian Inference

Inference queries were performed to estimate diabetes probability under different patient scenarios.

Examples included:

High HbA1c + high glucose.
Older adult + obesity.
High glucose + hypertension.
Low-risk patient profiles.
High-risk patient profiles.

The model demonstrated how diabetes probability changes when multiple risk factors are combined.

📊 Model Evaluation

The Bayesian Network was evaluated using:

Accuracy.
Precision.
Recall.
Classification Report.
Confusion Matrix.

Key Results

Accuracy ≈ 93%

Strong performance for non-diabetic predictions

Lower recall for diabetic cases due to class imbalance

The confusion matrix revealed that the model produced a relatively high number of false negatives, meaning some diabetic patients were misclassified as non-diabetic.

📈 Key Findings

Elevated HbA1c and blood glucose were the strongest predictors of diabetes.
Diabetes prevalence increased among patients with hypertension and heart disease.
Older age and higher BMI were associated with increased diabetes likelihood.
Combining multiple risk factors significantly increased predicted diabetes probability.

⚠️ Ethical Considerations & Limitations

Several important limitations and ethical concerns were identified:

Dataset imbalance reduced sensitivity for diabetes detection.
Discretization simplified some medical information.
Probabilistic models may reflect bias present in training data.
False negatives in healthcare predictions can be dangerous.
Bayesian Networks should support—not replace—clinical judgment.

🚀 Future Improvements

Potential future enhancements include:

Balancing the dataset.
Improving recall for diabetic predictions.
Testing continuous Bayesian approaches.
Adding additional clinical variables.
Comparing Bayesian Networks with other classification models.

👩‍💻 Author

Juliana Figueroa
M.S. Data Science – Grand Canyon University
GitHub: yuya04-maker
