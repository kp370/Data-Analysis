**Startup Profit Prediction using Multiple Linear Regression**

**Key Program Description:**

	•	Multiple linear regression implementation for startup profit prediction
	•	Advanced feature engineering with categorical variable encoding (one-hot encoding for states)
	•	Backward elimination technique for optimal feature selection
	•	Statistical analysis using both scikit-learn and statsmodels
 
**Output Summary:**

	•	Dataset: 50 startup companies with R&D spend, administration, marketing spend, state, and profit data
	•	Model Performance: R² score of 0.947 (94.7% accuracy) after optimization
	•	Key Finding: R&D spend is the only statistically significant predictor of profit
	•	Final Equation: Profit = 49,030 + 0.8543 × R&D Spend
	•	Feature Optimization: Backward elimination reduced 4 features to just R&D spend
 
**Important Technical Details:**

	•	One-hot encoding with dummy variable trap avoidance
	•	80/20 train-test split (40 training, 10 test samples)
	•	Comparison between full model and optimized model predictions
	•	Statistical significance testing at 0.05 level
 
**Usage Note**: Use the attached 50_Startups.csv file or a csv file with the required data structure when running the code.
