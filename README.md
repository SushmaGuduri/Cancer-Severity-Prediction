# Cancer Severity Prediction & Treatment Cost Analysis (2015–2024)

### The objective of this project is to analyze global cancer patient data collected between 2015 and 2024 to better understand the key factors influencing cancer diagnosis, severity, treatment costs, and patient survival outcomes. This analysis aims to provide actionable insights that can support healthcare decision-making and resource allocation.

### Cancer is a leading cause of death worldwide, with multiple factors affecting patient prognosis and healthcare costs. Early detection and personalized treatment strategies are critical to improving patient outcomes and optimizing medical expenses. However, the complexity of these factors requires advanced data analysis and machine learning models to uncover hidden patterns and predictive signals.

### The project involved:

👨🏻‍⚕️Performing exploratory data analysis (EDA) on cancer patient demographics, risk factors, treatment costs, and survival statistics.

👨🏻‍⚕️Identifying the most significant factors impacting cancer severity and survival rates.

👨🏻‍⚕️Developing predictive machine learning models to estimate cancer severity scores and forecast treatment costs.

👨🏻‍⚕️Comparing multiple algorithms to select the best performing model with good generalization.

### Methodology

💉Conducted detailed EDA including gender distribution, age analysis, risk factor correlation, country-wise incidence, yearly case trends, and survival distribution by cancer stage.

💉Isolated five key features influencing cancer severity: Smoking, Genetic Risk, Air Pollution, Alcohol Use, and Obesity Level.

💉Built and evaluated multiple ML models — Linear Regression, Ridge Regression, Random Forest, and XGBoost — using Mean Squared Error (MSE) and R-squared (R²) as performance metrics.

💉Applied regularization (Ridge Regression) to improve model robustness and address overfitting observed in Linear Regression.

💉Generated comprehensive visualizations and correlation analyses to support findings.

### Result
💊Ridge Regression emerged as the best model with an R² of 0.7923 and MSE of 0.2896, explaining approximately 79% of the variance in cancer severity scores.

💊Model improved prediction accuracy by 25%, enabling more reliable severity forecasting.

💊Treatment cost analysis showed an average 20% improvement in cost estimation precision, useful for healthcare budgeting and policy planning.

💊Survival analysis highlighted a 30% higher survival rate in early-stage cancer patients, emphasizing the importance of early detection programs.

💊The project delivered actionable insights for healthcare providers and policymakers to enhance patient outcomes and optimize treatment resource allocation.

### Tools & Technologies
🩺Python (Pandas, Scikit-learn, Matplotlib, Seaborn)

🩺Machine Learning Algorithms (Linear Regression, Ridge Regression, Random Forest, XGBoost)

🩺Exploratory Data Analysis & Visualization

### Impact
This project supports evidence-based healthcare strategies by identifying critical risk factors, predicting cancer severity accurately, and forecasting treatment costs — helping improve patient care and optimize medical resource management.


