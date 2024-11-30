# House Price Prediction Project

This project focuses on predicting house prices using advanced machine learning models. It utilizes the **House Prices - Advanced Regression Techniques** dataset from Kaggle and employs rigorous preprocessing, feature engineering, and model evaluation techniques to achieve accurate predictions. This project is heavy refernced on the kaggle Notebook 
**How I made top 0.3% on a Kaggle competition**. Instead of using a stacked model, we went with a simple 3 model comparison for the sake of learning the fundamentals of Ransom Forest, XGBoost and LightBGM. The dtata analysis was done with the guidance of the kaggle notebook
**Comprehensive data exploration with Python**.

---

## Models Used
### 1. **Random Forest Regressor**
- A robust ensemble method combining multiple decision trees to improve predictive accuracy.
- **Performance**: RMSLE = 0.1432.
- **Key Features**: Interpretable and reliable, ideal for understanding feature importance.

### 2. **XGBoost Regressor**
- An advanced gradient boosting algorithm building trees sequentially, correcting errors iteratively.
- **Performance**: RMSLE = 0.1395.
- **Strengths**: High accuracy, captures subtle patterns in data.

### 3. **LightGBM Regressor**
- A scalable gradient boosting method optimized for speed and large datasets.
- **Performance**: RMSLE = 0.1250 (Best-performing model).
- **Advantages**: Efficient memory usage, fast training, and strong predictive ability.

---

## Why LightGBM Performed Better
- **Efficiency**: Faster training through histogram-based splitting.
- **Scalability**: Effectively handled over 350 features in the dataset.
- **Memory Optimization**: Allowed rapid iterations and hyperparameter tuning.

---

## Key Takeaways
- Best Model: **LightGBM** for its balance of speed, scalability, and accuracy.
- Feature Engineering: Techniques like log transformations, derived features (e.g., total square footage), and categorical encoding significantly improved model performance.
- Evaluation Metric: Root Mean Squared Logarithmic Error (RMSLE) ensured fair assessment by penalizing large prediction errors.

Explore the project to see how each model was tuned and evaluated!
