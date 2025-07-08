# EY Biodiversity Challenge – Frog Presence Classification

**Description:**  
Built and optimized classification models to predict frog presence using climate and environmental data. Final model (ExtraTreesClassifier) achieved 83.1% accuracy and F1 score.

## Team Members
- Samarth Verma  
- Haeun Kim  
- Jayasree Lakshmi Narayanan  

---

## Project Overview
This project aimed to predict frog presence based on ecological and climate-related factors, contributing to biodiversity conservation insights. Various preprocessing and modeling strategies were explored.

---

## Methodology

### Data Preparation
- Feature selection using correlation analysis and domain knowledge  
- Handled class imbalance using `RandomOverSampler`  
- Removed outliers using Z-score method  
- Encoded categorical variables and standardized numerical features  

### Models Explored
- LightGBM  
- XGBoost  
- ExtraTreesClassifier (final model)  

---

## Final Model Performance
- **Model:** ExtraTreesClassifier  
- **Test Accuracy:** 0.831  
- **F1 Score:** 0.83  
- Strong generalization, reduced overfitting  

---

## Key Learnings
- Hyperparameter tuning significantly improved performance  
- Ensemble methods provided robust results  
- Proper data preprocessing (balancing + outlier handling) was critical to success  

