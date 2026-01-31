# sentiment-analysis-2024-presidential-candidates
This project focuses on analyzing public sentiment toward Indonesian 2024 presidential candidates (Anies Baswedan, Ganjar Pranowo, and Prabowo Subianto) using Twitter data. The study applies machine learning and natural language processing (NLP) techniques to classify tweets into positive, negative, and neutral sentiments.

An ensemble learning approach was implemented and evaluated using:
- Logistic Regression
- Random Forest
- Gradient Boosting
These models were combined using Soft Voting Ensemble to improve classification performance.
To address class imbalance, Synthetic Minority Over-sampling Technique (SMOTE) was applied. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, text vectorization using TF-IDF, model training, and performance evaluation.

## Dataset
The dataset used in this project was sourced from Kaggle:
**Indonesia Presidential Candidates Dataset 2024**  
https://www.kaggle.com/datasets/jocelyndumlao/indonesia-presidential-candidates-dataset-2024

The dataset contains Twitter data related to:
- Anies Baswedan  
- Ganjar Pranowo  
- Prabowo Subianto

## Repository Structure
- /data : Raw datasets (CSV files)
- /notebooks : Jupyter notebooks for preprocessing, analysis, and modeling
- /poster : Infographic poster summarizing project results
