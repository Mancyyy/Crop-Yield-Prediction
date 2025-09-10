# Crop-Yield-Prediction
Crop yield prediction using Decision Tree machine learning algorithm with data preprocessing, feature engineering, and evaluation metrics (MAE, MSE, R²). Uses soil, weather, and crop attributes to provide accurate yield forecasts and fertilizer recommendations, helping farmers improve productivity.


 🌾 Crop Yield Prediction using Machine Learning
This project focuses on predicting agricultural crop yields using Decision Tree algorithms and agricultural datasets. By analyzing soil health, weather patterns, crop type, and other agronomic factors, the system provides accurate yield forecasts and fertilizer recommendations to help farmers and agricultural planners improve productivity and revenue.

📌 Features
📊 Crop Yield Prediction – Estimates crop yield per acre based on soil, weather, and crop attributes.

🌱 Soil & Nutrient Analysis – Uses nitrogen, phosphorus, potassium (NPK), pH, and soil type as inputs.

☁️ Weather Integration – Considers rainfall, temperature, and seasonal conditions.

🧮 Decision Tree Model – Simple, interpretable ML model for yield forecasting.

🖥️ User Interface – GUI built using Tkinter for dataset upload, training, and prediction.

📈 Evaluation Metrics – Model assessed with MAE, MSE, and R² for reliability.

🔄 Actionable Insights – Provides fertilizer recommendations to boost yield.

🛠️ Tech Stack
Programming Language: Python

Libraries: Scikit-learn, Pandas, NumPy, Matplotlib

GUI: Tkinter

Algorithms: Decision Tree Regressor, Random Forest (tested), Linear Regression (tested)

Dataset: Agricultural crop production datasets (state, district, season, soil, rainfall, crop details)

⚙️ Installation
Clone the repository:

git clone https://github.com/your-username/crop-yield-prediction.git
cd crop-yield-prediction
Install required libraries:

pip install pandas numpy scikit-learn matplotlib
Run the application:

python crop_yield.py
🎮 How It Works
Upload Crop Dataset (CSV file).

Preprocess Data – Encodes categorical data, normalizes features.

Train Model – Uses Decision Tree to learn from training dataset.

Predict Yield – Upload test data and get predicted yield per acre.

Recommendations – Provides fertilizer ratios and insights based on soil and weather conditions.

📊 Results
Achieved ~85% accuracy on test datasets.

Key influencing factors: rainfall, soil type, and fertilizer use.

Predictions aligned closely with actual yields.

Provided actionable insights for farmers to optimize crop selection.

🚀 Future Enhancements
Use advanced ML models like Random Forest, XGBoost, or Neural Networks.

Integrate real-time weather APIs for dynamic predictions.

Expand to a web or mobile app for farmer-friendly usage.

Add IoT/sensor data for real-time soil and crop monitoring.

📜 Applications
📌 Helps farmers plan crops based on yield forecasts.

📌 Guides fertilizer usage for better productivity.

📌 Assists government and agri-business in resource planning.

📌 Supports research in precision agriculture.

