# 💳 Credit Card Fraud Detection

## Abstract
I implemented a machine learning pipeline to detect fraudulent credit card transactions. Using Python and popular libraries, I preprocessed the data, trained several models, and built a simple demo app.

## Libraries
- pandas, numpy, matplotlib, seaborn  
- scikit-learn, xgboost  
- imbalanced-learn (SMOTE)  
- shap  
- streamlit  

## Project Steps
1. **EDA & Preprocessing**  
   - Checked class imbalance  
   - Scaled features and applied SMOTE  
2. **Modeling**  
   - Trained Logistic Regression, Random Forest, XGBoost  
   - Compared models using AUC, precision, recall  
3. **Explainability**  
   - Used SHAP to see which features matter most  
4. **Demo App**  
   - Created a Streamlit interface to upload CSVs and view fraud predictions  

## Results
- **Best Model (XGBoost):** AUC ≈ 0.99, Precision ≈ 0.92, Recall ≈ 0.96

## Quick Start
```bash
git clone https://github.com/YOUR_USERNAME/Fraud-Detection
cd Credit-Card-Fraud-Detection
pip install -r requirements.txt
python src/train.py            # train models
streamlit run src/app.py       # launch demo
