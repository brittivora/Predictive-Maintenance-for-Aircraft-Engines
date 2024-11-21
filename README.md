# Predictive-Maintenance-for-Aircraft-Engines
## "Because Grounding a Plane is More Expensive than Predicting the Future!"

## Overview
This project explores the use of machine learning techniques to implement predictive maintenance for aircraft engines by estimating the Remaining Useful Life (RUL) of engine components. Leveraging real-time sensor data, the models aim to optimize maintenance schedules, reduce unplanned downtime, and improve safety in the aviation industry.

## Key Features
- **Dataset:** NASA Turbofan Engine Degradation Simulation Dataset
- **Techniques:**
  - Data preprocessing: Feature scaling, correlation analysis
  - Machine learning models: Linear Regression, Random Forest, XGBoost
  - Model evaluation: Root Mean Squared Error (RMSE), R-squared (R²)
  - Regularization techniques to address overfitting (Ridge and Lasso Regression)
- **Tools & Libraries:** 
  - Python
  - Scikit-learn
  - XGBoost
  - Matplotlib
  - Pandas
  - NumPy

## Project Objectives
1. Develop machine learning models for RUL prediction using real-world sensor data
2. Address overfitting and enhance model generalization
3. Explore feature selection techniques for improved performance
4. Lay a foundation for applying predictive maintenance to other industrial systems

## Implementation Highlights
### Data Preparation
- Exploratory Data Analysis (EDA) to identify key trends and insights
- Feature selection using correlation analysis to reduce dimensionality
- Train-test split and feature scaling using `StandardScaler`

### Model Development
- **Linear Regression:** Basic regression model as a baseline
- **Random Forest:** Ensemble learning approach for non-linear relationships
- **XGBoost:** Gradient boosting for advanced predictions
- Regularization methods (Ridge and Lasso) to prevent overfitting

### Challenges Addressed
- Overfitting in models, mitigated through hyperparameter tuning and regularization
- Poor generalization tackled via cross-validation and improved data preprocessing

### Future Enhancements
- Advanced feature engineering and data augmentation.
- Integration with real-world predictive maintenance systems.
- Exploring transfer learning for improved generalization.

## Acknowledgments
This work was conducted as part of my Bachelor of Data Science program at Somaiya Vidyavihar University.

## License
This project is licensed under the MIT License
