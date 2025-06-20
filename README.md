# Pima-Indians-Diabetes
This project applies machine learning techniques to predict the likelihood of diabetes in patients using the Pima Indians Diabetes Dataset. The dataset contains key clinical measurements such as glucose levels, BMI, age, and blood pressure. The primary goal is to determine which classification algorithm Support Vector Machine (SVM), Gradient Boosting Machine (GBM), or Random Forest (RF) provides the best predictive performance using evaluation metrics like accuracy, recall, F1 score, and AUC-ROC.

To ensure reliable modeling, the dataset underwent careful preprocessing: zero values in medically critical fields were replaced with NaN, missing data were imputed using median values, and standardization was applied where necessary. Each algorithm was fine-tuned using GridSearchCV for hyperparameter optimization and then evaluated using confusion matrices, ROC curves, and metric comparison charts.

This repository is designed for students, researchers, and professionals interested in healthcare analytics and model comparison.
