# Students-Health-Predictor
Overview -
This research aims to predict student depression using machine learning approaches. A logistic regression model was developed to predict if a student is likely to be depressed using a structured dataset combining behavioral, academic, psychological, and demographic variables.\

Objective -
The primary aim is to mirror a real-world mental-health screening scenario in which timely detection of depressive tendencies enables targeted support interventions. By transforming raw survey responses into actionable risk scores, this model serves as a prototype for educational institutions and counselors seeking data-driven tools to promote student well-being.

Key Highlights -
Data Source:        A CSV dataset containing student-related features such as academic pressure, CGPA, dietary habits, sleep duration, suicidal thoughts, etc.
Target Variable:    Depression (Binary classification: 0 = No Depression, 1 = Depression).
Feature encoding:   one-hot encoding for categorical variables and scaling of numerical features.
Model development:  Training and cross-validation of a logistic regression classifier.
Evaluation metrics: accuracy, precision, recall, F1-score, and ROC AUC analyses.
Visualization:      confusion matrices, ROC curves, and feature-importance plots.

Workflow Overview - 
1. Exploratory Data Analysis (EDA) -
- Visualized class distribution of depressed vs non-depressed students.
- Analyzed correlations between depression and other features (e.g., sleep, study hours, CGPA).
- Used heatmaps and bar charts to uncover patterns.

2. Data Preprocessing -
- Handled missing values and removed irrelevant columns.
- Encoded categorical variables using LabelEncoder/OneHotEncoder.
- Normalized numerical features where needed.

3. Model Building -
- Applied Logistic Regression as the classification algorithm.
- Split data into training and testing sets using train_test_split.
- Trained the model and evaluated using accuracy, precision, recall, and F1-score.

4. Model Evaluation -
- Achieved strong classification performance on test data.
- Visualized results using a confusion matrix.

5. Prediction on Custom Input -
- Accepted user input via form or manual row creation.

Tools and Technologies - 
- Python (Jupyter Notebook)
- Pandas and NumPy for data manipulation
- Seaborn and Matplotlib for visualization
- Scikit-learn for machine learning
- Logistic Regression model pipeline with preprocessing steps

Conclusion -
- The project demonstrated how logistic regression can be effectively,successfully used to apply real world mental health issues.
- With adequate preprocessing and EDA, depression risks can be predicted using observed behaviors and academic demands.
- The program also allows for bespoke forecasts based on particular student profiles.  
Displayed class probability and predicted label.

