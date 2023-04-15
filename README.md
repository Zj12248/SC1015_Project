# SC1015_Project Suicide Prediction

## About
Our project aims to explore key indicators of suicide and developing models that can help identify and predict those at risk of suicide.

Requirements for running notebook
- geopandas
- graphviz

Datasets from 
- https://www.kaggle.com/datasets/omkargowda/suicide-rates-overview-1985-to-2021 (Suicide Data)
- https://www.kaggle.com/datasets/andradaolteanu/country-mapping-iso-continent-region (Country-region Mapping)

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
-----------------

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
