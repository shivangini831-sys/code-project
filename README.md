# Forecasting of Smart City Traffic Patterns
A machine learning project to forecast smart city traffic patterns using Decision Trees. Developed during my internship with Upskill Campus & UniConverge Technologies (UCT), it predicts congestion across junctions, analyzes peak traffic times, and provides insights for urban planning and smart transport systems.

📌 Project Overview

This project focuses on building a traffic forecasting model for smart cities to help governments and city planners manage congestion and optimize infrastructure planning. By applying machine learning techniques, the system forecasts traffic flow across junctions and provides insights for real-time decision-making.

👉 This work was completed as part of my Industrial Internship with Upskill Campus & UniConverge Technologies Pvt. Ltd. (UCT).

📂 Problem Statement

• Rapid urbanization and population growth have led to severe traffic congestion.
• Governments require predictive models to manage traffic peaks effectively.
• The objective is to forecast traffic patterns (flow, congestion, travel times) across city junctions using historical and contextual data.

⚙️ Existing Solutions and Challenges

• Statistical Models (ARIMA, Exponential Smoothing): Simple but fail to capture complex traffic behaviors.
• Machine Learning Models (SVM, Random Forests): Better but require extensive feature engineering.
• Deep Learning (RNN, CNN): Accurate but need huge datasets and are computationally intensive.
• Simulation Models: Depend on accurate input data; limited real-time adaptability.

💡 Proposed Solution

• Applied Decision Tree Algorithm for forecasting traffic patterns.
• Handles both categorical and continuous features.
• Provides interpretability with feature importance.
• Robust against missing values and outliers.
• Can be extended using ensemble methods (Random Forest, Gradient Boosting).

📂 Project Workflow

• Data Collection: Historical traffic data including time, weather, events.
• Data Preprocessing: Handling missing values, feature engineering, encoding.
• Model Training: Applied Decision Tree algorithm.
• Model Evaluation: Measured performance using MAE, RMSE, and MAPE.
• Visualization: Predicted traffic patterns across four junctions.
• Insights: Identified peak congestion hours, weather/event impacts.

📊 Performance & Results

• Predictions for Junctions 1, 2, and 4 were highly accurate.
• Junction 3 showed moderate accuracy (further feature engineering required).
• Metrics Used: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE).
• Visualized traffic flows and congestion trends for better interpretability.

🛠 Tech Stack

• Python
• Pandas, NumPy – Data Preprocessing
• Scikit-learn – Machine Learning (Decision Tree)
• Matplotlib, Seaborn – Data Visualization

📚 Learnings

• Gained hands-on experience with Machine Learning for time-series forecasting.
• Understood how Decision Trees work for real-world traffic data.
• Improved knowledge of feature engineering, model evaluation, and visualization.
• Learned how data science supports smart city development.

🔮 Future Work

• Feature engineering with seasonality, holidays, and road incidents.
• Incorporating real-time traffic feeds.
• Exploring hierarchical and ensemble methods (Random Forest, Gradient Boosting).
• Adding spatial dependencies using GIS data.
• Building dynamic updating models to adapt to evolving traffic patterns.

🤝 Internship Acknowledgement

This project was developed during my 6-week Industrial Internship with Upskill Campus and UniConverge Technologies Pvt. Ltd. (UCT), where I worked on real-world smart city data science applications.
