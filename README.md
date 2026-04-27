Academic Performance Prediction of Students 
Using Explainable Machine Learning Ensemble 
Techniques 
<img width="870" height="597" alt="image" src="https://github.com/user-attachments/assets/f4d459eb-2b44-4a33-aa20-f53e4776e1cb" />


📖 Project DescriptionThis project implements an explainable machine learning framework to predict student academic success (Pass/Fail). It addresses the "black-box" nature of complex algorithms by integrating SHAP (SHapley Additive exPlanations) to provide transparency and interpretability for educators.

🛠️ System ArchitectureThe system follows a structured workflow as outlined in the research:

Data Collection: Uses a student performance dataset containing demographic, academic, and socio-economic features.

Data Preprocessing: Includes handling missing values, encoding categorical data (like gender and lunch type), and normalizing numeric data.

Data Splitting: The dataset is divided into 70% Training and 30% Testing sets.Ensemble Modeling: Trains two primary classifiers: Random Forest and XGBoost.

Soft Voting: Combines the probabilities from both models to generate a final prediction.

SHAP Analysis: Provides feature importance and interpretation to explain prediction outcomes.

🚀 Key Features

Hybrid Ensemble: Combines Random Forest and XGBoost for robust and accurate predictions.
Explainable AI (XAI):Uses SHAP to identify and visualize the most significant variables affecting performance.

High Performance: Achieved an overall classification accuracy of 91%.

📊 Results & Insights

Top Predictors:The most critical factors influencing student success were identified as lunch type, test preparation course, and parental education.

Model Accuracy: The ensemble model demonstrated high precision and recall for both 'Pass' and 'Fail' classes.📂 Repository Structuredata/: Student performance dataset.notebooks/: Python implementation of the ensemble model and SHAP analysis.results/: Confusion matrices and SHAP summary plots.

📝 Citation
If you use this work, please cite the research:Khushi, "Academic Performance Prediction of Students Using Explainable Machine Learning Ensemble Techniques," Chitkara University, 2026. How to add this to your GitHub.
