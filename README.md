# AI-Driven-Cardiovascular-Disease-Prediction-with-Personalized-Nutrition
Machine learning system predicting cardiovascular disease risk  with personalized DASH diet recommendations using patient lifestyle data

## Dataset
- 70,000 patients
- Features: Age, BMI, cholesterol, lifestyle factors
- Target: Cardiovascular disease

## Results
- **Best Model**: LightGBM (64.3% accuracy, 0.696 AUC)
- **Risk Tiers**: Low/Medium/High/Very High (0-100 score)
- **Recommendations**: Sodium limits, exercise, weight loss

## Usage
```bash
pip install pandas numpy scikit-learn xgboost lightgbm tensorflow shap
jupyter notebook PersonalNutriAI_Complete.ipynb
```

## Models
- Logistic Regression, Random Forest, XGBoost, LightGBM, Neural Network
- SHAP interpretability
- K-means patient clustering

## Output
- 9 visualizations
- Trained models
- Patient risk reports
- Personalized nutrition plans
