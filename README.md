# Analysis of Cancer Levels

The dataset was downloaded online from Kaggle and used as a CSV file. The original dataset consists of 1 000 cancer patient records with accompanying 24 different attributes (excluding the patient ID). MySQL was then used to create and extract 3 tables corresponding to the 3 available cancer levels; low, medium, and high; for better analysis.

# Models

Our Machine Learning project consists of a total of 12 models.

6 Logistic Regression Models were created and tested. LR-A-1, a Scikit-Learn Logistic Regression model, and two more: LR-A-2 trained on data features selected by mutual information, and LR-A-3 trained on manually feature-selected data. Along with three SGD Classifier Logistic Regression models, LR-B-1 a basic model, LR-B-2 trained on mutual information based selected features, and LR-B-3 trained on features that were manually selected.

6 Random Forest Models were created and tested. RF-A-1, a Scikit-Learn Random Forest model, and two more: RF-A-2 trained on data features selected by mutual information, and RF-A-3 trained on manually feature-selected data. Along with three XGBoost Random Forest models, RF-B-1 a basic model, RF-B-2 trained on mutual information based selected features, and RF-B-3 trained on features that were manually selected.
