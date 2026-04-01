# Cardiovascular-Disease-Prediction
Cardiovascular Disease Prediction using Machine Learning techniques with end-to-end pipeline including data cleaning, visualization, model comparison, and deployment-ready model saving. Achieved ~73.67% accuracy with Random Forest as the best model.
## Features 
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA) with visualizations
- Feature Scaling using StandardScaler
- Multiple ML Models Comparison:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree 
  - Random Forest
  - Support Vector Machine (SVM)
- Model Evaluation using Accuracy & Classification Report
- Best Model Selection
- Model Saving using Joblib

## Dataset
- Dataset used: Cardiovascular Disease Dataset
- Contains features like:
  - Age
  - Gender
  - Height & Weight
  - Blood Pressure (ap_hi, ap_lo)
  - Cholesterol
  - Glucose
  - Smoking, Alcohol Intake, Physical Activity
- Target variable:
  - cardio (0 = No Disease, 1 = Disease)
  
## Exploratory Data Analysis
- The project includes:
  - Heart disease distribution
  - Age distribution
  - Age vs Disease relationship
  - Cholesterol & Glucose impact
  - Correlation heatmap
    
## Technologies Used
  - Python 
  - Pandas & NumPy
  - Matplotlib & Seaborn
  - Scikit-learn
  - Joblib
## Machine Learning Models Used
| Model               | Accuracy           |
| ------------------- | ------------------ |
| Logistic Regression | ~73.01%            |
| KNN                 | ~70.35%            |
| Decision Tree       | ~73.31%            |
| Random Forest       | **~73.67% (Best)** |
| SVM                 | ~73.35%            |

Best Model: Random Forest<br>
The Random Forest model achieved the highest accuracy and was selected as the final model.
## Results
- Achieved around 73% accuracy
- Random Forest performed best among all models
- Balanced performance across precision, recall, and F1-score
## Future Improvements
- Hyperparameter tuning for better accuracy
- Feature engineering
- Deployment using Flask/Streamlit
- Deep learning models for improved performance
