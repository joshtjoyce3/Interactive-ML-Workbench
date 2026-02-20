# Interactive-ML-Workbench
Machine Learning analysis identifying high-value customer segments and predicting purchase behavior using XGBoost.

🎯 ShopNow Purchase Prediction: Strategic ML Analysis
This project uses an Interactive Machine Learning Workbench to predict customer purchase behavior over a 30-day window. By comparing multiple modeling architectures, I developed a strategy to reduce churn and maximize revenue lift for the ShopNow platform.

💰 Business Impact & ROI
Rather than focusing solely on technical accuracy, I prioritized economic lift by implementing a custom cost-benefit matrix:


False Positive (FP) Cost: -$5 (Cost of unnecessary promotion).


False Negative (FN) Cost: -$10 (Opportunity cost of a missed sale).


Winning Model: XGBoost.


Total Lift: Achieved a $1,115 improvement over the baseline "do-nothing" strategy.

🛠️ Methodology & Technical Approach

Data Preparation: Cleaned the ShopNow dataset by removing non-predictive features and handling outliers using a Clip IQR strategy to prevent overfitting.


Model Comparison: Evaluated four distinct algorithms—Ridge, Lasso, Random Forest, and XGBoost—using an 80/20 train/test split to ensure the model captured complex, non-linear patterns in the data.


Optimization: While XGBoost had lower precision, it achieved the highest Recall, successfully identifying the largest number of actual buyers to maximize total value.

📈 Strategic Insights
The model identified the following key drivers for customer conversion:


Recency: The number of days since the last purchase is the strongest predictor of future activity.


Average Order Value: Spending habits significantly influence the 30-day purchase likelihood.


High-Frequency Categories: Apparel, Sports, and Groceries show higher predictive power for recurring sales.

💡 Recommendations
Target customers at the 20-day "no-purchase" mark with personalized promotions in high-frequency categories to prevent churn.

Implement a loyalty program for high-spenders to leverage the influence of average order value on retention.

Note: The interactive GUI framework was provided as part of an MBA coursework assignment. All data analysis, feature engineering, model selection, and financial impact calculations are my original work.
