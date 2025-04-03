# 📊 AI-Driven Time Series Forecasting

## 🔍 Project Overview
This project focuses on time series forecasting for product demand using multiple machine learning models: **XGBoost, Prophet, and a Hybrid Model**. The objective is to predict future sales trends for various products based on historical data and evaluate model performance using **Mean Absolute Percentage Error (MAPE)**.

## 📂 Dataset
- **Historical Sales Data**: Sales figures over multiple quarters.
- **Forecasted Data**: Model-generated predictions for upcoming quarters.
- **Product Categorization**: Each product falls under **Sustaining, Declining, or New Product Introduction (NPI)** lifecycle.

## 🛠️ Models Used
### 1️⃣ **XGBoost**
   - Gradient boosting algorithm known for handling non-linearity and seasonality.
   - Performs well for sustaining products with stable trends.
   
### 2️⃣ **Prophet**
   - Developed by Facebook, ideal for capturing trend and seasonality effects.
   - Works best for declining and NPI lifecycle products.
   
### 3️⃣ **Hybrid Model (XGBoost + Prophet)**
   - Combines the strengths of both models.
   - Provides better accuracy when individual models exhibit higher errors.

## 📈 Visualizations
### 🔹 **Time Series Forecasting Graphs**
- **20 graphs**, each displaying actual vs. predicted values for all three models.
- Helps analyze forecasting accuracy and model performance per product.

### 🔹 **MAPE Comparison Table**
- Displays model errors across different products.
- Highlights the best-performing model for each product.

### 🔹 **Bar Graph - Actual vs. Predicted**
- Compares predicted sales to actual sales.
- Helps understand overall forecasting effectiveness.

## 🔑 Key Findings
✅ **XGBoost** is the best choice for sustaining products with stable demand trends.
✅ **Hybrid Model** improves accuracy when individual models struggle.
✅ **Prophet** works well for declining and NPI lifecycle products but is inconsistent elsewhere.

## 🏆 Conclusion
This project demonstrates that no single forecasting model is universally optimal. The choice of the model depends on the **product lifecycle**, and a hybrid approach can significantly enhance forecasting accuracy. The insights from this analysis can aid **inventory management, demand planning, and resource allocation**.

## 🚀 How to Run the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the forecasting script:
   ```bash
   python forecasting.py
   ```

## 📜 Acknowledgments
Special thanks to the **AI & Data Science community** for open-source tools and methodologies that made this project possible.

---
_🔗 Connect with me on GitHub or LinkedIn for more AI projects!_ 🚀

