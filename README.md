# Malaria-Prediction-Project
This project aims to predict the presence of malaria using a dataset with several features. Various machine learning models are tested and compared in terms of performance after fine-tuning their hyperparameters.  

## Dataset Overview
A labeled data set of 17 symptoms of 337 patients of region in africa with a target label as 1 for malaria desease and 0 for no malaria. 

## Data Format


Format: csv 


### Models Used  
- Random Forest  
- Adaptive Boosting (AdaBoost)  
- Gradient Boosting  
- XGBoost  
- CatBoost  

### Installation  
Before running the project, make sure to install the required libraries:  

```bash
pip install numpy pandas scikit-learn xgboost catboost matplotlib seaborn
```

### Usage  

1. **Launch Jupyter Notebook**  
   ```bash
   jupyter notebook
   ```
2. **Open the file**: `Malaria_Prediction_Project.ipynb`  
3. **Run all cells** to see data preprocessing, model training, and performance comparison.  

### Results  
The models are evaluated using several metrics, including accuracy, precision, recall, and AUC-ROC.  
