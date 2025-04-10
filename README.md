Customer Happiness Prediction for Logistics Startup
Predicting Customer Satisfaction Using Survey Data

🔗 GitHub Repository: Project Link

📌 Project Overview
Objective: Build a machine learning model to predict customer happiness (0 = Unhappy, 1 = Happy) based on survey responses from a fast-growing logistics startup.

Business Impact:

Helps prioritize operational improvements.

Identifies key drivers of customer satisfaction.

Optimizes future survey questions by removing less impactful features.

Success Metric: Achieve ≥73% accuracy in classification.

📊 Dataset Description
The dataset consists of customer survey responses (1-5 Likert scale) on:

X1: Order delivered on time

X2: Contents as expected

X3: Ordered everything desired

X4: Good price

X5: Courier satisfaction

X6: App usability

Target Variable (Y):

0 = Unhappy customer

1 = Happy customer

🔍 Project Workflow
1️⃣ Exploratory Data Analysis (EDA)
Checked class distribution (balanced dataset).

Analyzed feature correlations (heatmap).

Visualized response distributions for each question.

2️⃣ Data Preprocessing
No missing values found.

Features were already scaled (1-5 ratings).

Train-test split (70-30 ratio).

3️⃣ Model Selection & Training
Tested multiple algorithms:

Model	Accuracy	ROC-AUC	Key Insight
Random Forest	78.9%	0.865	Best overall
SVM	73.7%	0.677	High recall
Logistic Regression	68.4%	0.711	Simple baseline
XGBoost	68.4%	0.748	Good potential
LightGBM	60.5%	0.707	Underperformed
4️⃣ Feature Importance Analysis
Top 3 Drivers of Happiness:

Courier satisfaction (X5)

On-time delivery (X1)

Good price (X4)

Least Important: App usability (X6) → Can be dropped in future surveys.

5️⃣ Hyperparameter Tuning
Used GridSearchCV to optimize Random Forest.

Improved stability via KFold Cross-Validation (avg. accuracy: 60-76%).

6️⃣ Addressing Class Imbalance
Tested class weighting in Logistic Regression (failed for minority class).

Random Forest naturally handled imbalance better.

7️⃣ Ensemble Learning (Voting Classifier)
Combined RF, SVM, XGBoost → 71% accuracy.

Not better than standalone RF, but more robust.

📌 Key Insights & Business Recommendations
✔ Operational Focus Areas: Courier performance (X5) and on-time delivery (X1) are critical.
✔ Survey Optimization: Remove X6 (App usability) without losing predictive power.
✔ Model Stability: More data needed to reduce KFold variance (48-76% accuracy fluctuations).

🚀 Conclusion & Hiring Manager Notes
This project demonstrates my ability to:
✅ Solve real business problems with data-driven ML models.
✅ Analyze feature importance to derive actionable insights.
✅ Optimize model performance (achieved 78.9% accuracy with Random Forest).
✅ Communicate technical results clearly for business stakeholders.

Why This Matters for Your Team:

I can build and deploy predictive models that drive customer satisfaction.

I identify key business drivers beyond just model accuracy.

I adapt to challenges (class imbalance, small dataset) with robust solutions.

🔗 GitHub Code: Project Link | LinkedIn: https://www.linkedin.com/in/jyothirmai-2a5bab62/

📩 Let’s Connect!
Interested in how this approach can apply to your business? Let’s discuss!
📧 Email: jyothirmayee.palle@gmail.com 

🌟 Key Skills Demonstrated:
Python Scikit-Learn Random Forest Feature Importance Hyperparameter Tuning Ensemble Learning Business Analytics

