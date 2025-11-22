🚗 Salifort Motors: Employee Retention Project

<!-- PROFESSIONAL BADGES: Highlight key technologies and project status -->

📌 Business Problem: Addressing High Attrition

The Human Resources department at Salifort Motors is grappling with an unacceptably high employee turnover rate of 16.6%. This attrition poses a substantial financial burden through escalated recruitment, training, and lost institutional knowledge.

Objective: To develop and deploy a highly predictive Machine Learning model capable of forecasting which employees are at the highest risk of resignation.

Business Value: Implement a proactive, data-driven retention strategy to reduce turnover costs and stabilize the workforce.

⚙️ Methodology: Machine Learning Approach

The analysis was conducted on a dataset comprising 15,000 employee records, focusing on key variables such as workload, satisfaction, tenure, and performance evaluation.

Exploratory Data Analysis (EDA): Critical risk segments were identified: notably, employees managing 6+ projects (overload) and employees in the 4-year tenure bracket (stagnation).

Model Selection: The Random Forest Classifier was selected for its robust performance, resistance to overfitting, and superior ability to measure complex, non-linear feature interactions.

Feature Importance: Satisfaction Level, Number of Projects, and Average Monthly Hours were confirmed as the primary and strongest predictors of employee flight risk.

🏆 Champion Model Performance (Random Forest on Test Set)

The final model demonstrates outstanding diagnostic and predictive capabilities, achieving results suitable for operational implementation:

Metric

Score

Interpretation

AUC Score

93.8%

Excellent discriminatory power; the model reliably separates employees who will stay from those who will leave.

Accuracy

96.2%

Overall correct classification rate.

Precision

87.0%

When the model flags a 'flight risk' (positive prediction), it is correct 87% of the time, minimizing unnecessary HR intervention costs.

Recall

90.4%

The model successfully captures the vast majority of actual resigning employees, ensuring few high-risk individuals are missed.

💡 Actionable Insights and Recommendations

The predictive power of the model is translated into the following actionable, data-backed strategies for the HR Leadership Team:

Workload Management: Implement a strict upper limit of 5 projects per employee. Workloads of 6 or more are proven to be the leading indicator of burnout and attrition among high performers.

Mid-Career Retention Strategy: Launch a targeted retention program (e.g., career progression interviews, mentorship) for employees approaching the 4-year tenure mark to address career stagnation risk.

Performance Metric Alignment: Decouple high performance reviews from excessive working hours. The current system is rewarding unsustainable monthly hours (200+), leading to the loss of top talent.

This project was completed as the capstone for the Google Advanced Data Analytics Professional Certificate.
