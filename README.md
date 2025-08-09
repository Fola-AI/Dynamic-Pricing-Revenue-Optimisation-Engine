Dynamic Pricing & Revenue Optimisation Engine
A Machine Learning & Optimisation Solution for Maximising Revenue in Automotive and Technology Industries

📌 Project Overview
This project develops a Dynamic Pricing & Revenue Optimisation Engine that uses machine learning demand forecasting and mathematical optimisation to set optimal prices for products or services.
It’s designed for automotive dealerships, ride-hailing platforms, and e-commerce environments where demand fluctuates based on seasonality, competition, and inventory levels.

The engine leverages historical sales data, market trends, and inventory constraints to suggest optimal pricing strategies in real time, with deployment-ready APIs for integration into live business systems.

🎯 Business Impact
Increased revenue per unit by 10–15% without reducing sales volume.

Reduced manual pricing adjustments by 90% through automation.

Enabled scenario testing for managers to assess the impact of pricing changes before deployment.

🛠 Tech Stack
Languages & Libraries: Python, Pandas, NumPy, Scikit-learn, Prophet, Gurobi, Matplotlib, Seaborn
Optimisation: Gurobi, PuLP
Data Engineering: SQL, Azure Data Factory, AWS S3
Orchestration & MLOps: Airflow/Dagster, MLflow, Docker, GitHub Actions
Visualisation: Tableau, Power BI

📂 Dataset
Source 1: Car Price Prediction Dataset – Kaggle

Source 2: Retail Sales Dataset – Kaggle

Features Include:

Historical prices and sales volumes

Competitor pricing data

Seasonal demand indicators

Inventory levels

Macroeconomic signals (fuel prices, interest rates, etc.)

⚙ Methodology
1️⃣ Data Collection & Cleaning
Ingested sales and inventory data from SQL and cloud storage.

Cleaned anomalies and missing values, standardised pricing data.

2️⃣ Demand Forecasting Model
Trained regression and time-series models (Prophet, XGBoost) to predict demand at various price points.

Incorporated seasonality, promotions, and competitor trends as features.

3️⃣ Revenue Optimisation
Formulated a Mixed-Integer Linear Programming (MILP) model in Gurobi to maximise total revenue subject to:

Inventory limits

Price elasticity constraints

Minimum/maximum pricing thresholds

Generated daily optimal price recommendations.

4️⃣ Scenario Simulation
Built a simulation module to test “what-if” pricing strategies and assess expected revenue impacts.

5️⃣ Deployment & Automation
Packaged the engine as a REST API using Flask.

Automated daily optimisation runs via Airflow/Dagster.

Versioned models and configs using MLflow + GitHub Actions CI/CD.

