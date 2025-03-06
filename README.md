# Housing Price Prediction using Machine Learning  
### University-Level Project - DATA*6100  

**Author:** Harshal Kakaiya  
**Instructor:** Dr. Mihai Nica  
**Course:** DATA*6100 (Project 1)  

## Project Overview  
This project aims to predict house sale prices using the AMES housing dataset. The workflow includes:  
- **Exploratory Data Analysis (EDA)** to identify key trends and relationships.  
- **Data Preprocessing & Feature Engineering** for handling missing values, scaling features, and transforming categorical data.  
- **Modeling & Evaluation** by implementing multiple regression algorithms, including Ridge Regression, K-Nearest Neighbors, Random Forest, and XGBoost.  
- **Hyperparameter Tuning** using Grid Search Cross-validation to optimize Ridge Regression for the best bias-variance trade-off.  

The final Ridge Regression model achieved a **Root Mean Squared Error (RMSE) of 18,407** on the test dataset, demonstrating strong predictive performance.  

## Installation & Requirements  
To run this project, install the necessary Python libraries:  
```bash  
pip install numpy pandas scikit-learn matplotlib seaborn xgboost  
```  

## Usage  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/harshalk612/housing-data-price-prediction.git  
   cd housing-data-price-prediction  
   ```  
2. Open the Jupyter Notebook:  
   ```bash  
   jupyter notebook housing_price_prediction.ipynb  
   ```  
3. Run the notebook to execute the analysis and model training.  

## Results  
- Ridge Regression was selected as the best model based on RMSE.  
- The final model effectively balanced **bias and variance**, with hyperparameter tuning optimizing the alpha parameter.  

## Acknowledgment  
This project was completed as part of the **DATA*6100 course at the University of Guelph** under the supervision of **Dr. Mihai Nica**.  
