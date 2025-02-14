# Vehicle Insurance Fraud Prediction

## Project Overview
This project is focused on predicting fraudulent vehicle insurance claims using machine learning. Fraud detection is crucial for insurance companies to minimize losses and ensure fair policy pricing. Identifying fraudulent claims early can save significant time and resources for both companies and policyholders, as well as reduce insurance premiums by eliminating false claims. The project builds a classification model that helps identify high-risk claims based on historical data.

## Technologies Used
- Python: Programming language for data processing and machine learning
- scikit-learn: For model building, data preprocessing, and evaluation
- XGBoost: Gradient boosting framework used for building a high-performing classification model
- Pandas: Data manipulation and analysis
- NumPy: Numerical computation
- Matplotlib & Seaborn: Data visualization tools
- SMOTE: For handling imbalanced datasets by oversampling the minority class
- Jupyter Notebook: For exploratory data analysis and model building

## How to Run
To replicate this project,
1. Clone the repository to your local machine.
```bash
   git clone https://github.com/your-username/vehicle-insurance-fraud-prediction.git
```
2. Install the necessary dependencies by running:
```bash
pip install -r requirements.txt
```
3. Open and run the Jupyter notebook:
```bash
jupyter notebook Predict_vehcilce_insurance_fraud.ipynb
```
4. Run the notebook cells sequentially to preprocess the data, train models, and evaluate the results.

## Project Results
The model successfully predicts fraudulent claims with high accuracy. The feature importance analysis also provides insights into which factors are most influential in determining fraud.
The best-performing model, XGBoost, achieved the following metrics:
- Recall: 0.97
- ROC-AUC Score: 0.82

Key insights: Feature Importance showed that the Base policy, fault, and address change were some of the most important features influencing fraud predictions.
The model is able to detect potential fraudulent claims effectively, helping reduce exposure to financial risks.

## Future Improvements
- Testing more advanced techniques like deep learning.
- Engineering new features to improve performance.
- Experimenting with different datasets for broader applicability.
