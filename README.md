# SC1015_Project Suicide Prediction

## About
Our project aims to explore key indicators of suicide and develop models that can help identify and predict those at risk of suicide.

Package requirements for running notebook
- geopandas
- graphviz

Datasets from 
- https://www.kaggle.com/datasets/omkargowda/suicide-rates-overview-1985-to-2021 (Suicide Data)
- https://www.kaggle.com/datasets/andradaolteanu/country-mapping-iso-continent-region (Country-region Mapping)

## Contributions
- Zj12248 - Data extraction, Data Preprocessing, Data visualisation, Random Forest, XGBoost
- Vithun - Classification Tree, Presentation Structure, Problem Ideation

## Problem Definintion
- Are we able to predict if a person is of high or low suicide risk?
- Which model would be the best to predict it?

## Models Used
1. Decision Tree
2. Random Forest
3. XGBoost

## Conclusion
- Random Forest is the optimal model among the 3 to predict suicide risk
- approximately 93% accuracy, with 95% True Positive Rate, thus is a good predictor of suicide risk
- GDP per capita have extremely weak linear correlation values with suicide rates(contrary to instinctual belief), however random forest model does list it as the most important feature
- We have to focus on helping Europeans, Males, and older people as they are of highest suicide risk.

## What did we learn from this project
- one hot encoding, min-max scaling
- importance features
- Random Forest, XGBoost - machine learning models
- geopandas , graphviz

## File Descriptions

SC1015_Project_SuicideRisk.ipynb
- A Jupyter Notebook containing the main source code for the project.

SC1015 Presentation.pptx
- Presentation Slides
    
README.txt (this file)
- Basic information about the project repository.

SC1015_Transcript.pdf
- A PDF copy of the transcript for the video presentation 
    
continents2.csv
- Country mapping Dataset

master.csv
- Suicide Rates from 1985-2021 dataset

## References
- https://machinelearningmastery.com/why-one-hot-encode-data-in-machine-learning/
- https://towardsdatascience.com/xgboost-theory-and-practice-fb8912930ad6
- https://medium.com/@gabrieltseng/gradient-boosting-and-xgboost-c306c1bcfaf5
- https://towardsdatascience.com/beginners-guide-to-xgboost-for-classification-problems-50f75aac5390
- https://towardsdatascience.com/understanding-random-forest-58381e0602d2
- https://machinelearningmastery.com/implement-random-forest-scratch-python/
- https://towardsdatascience.com/everything-you-need-to-know-about-min-max-normalization-in-python-b79592732b79
- https://towardsdatascience.com/having-an-imbalanced-dataset-here-is-how-you-can-solve-it-1640568947eb
