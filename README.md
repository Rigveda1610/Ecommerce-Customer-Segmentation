 Project Overview
This project focuses on analyzing e-commerce customer behavior by segmenting customers using **RFM (Recency, Frequency, Monetary) Analysis** and predicting future sales trends using **Time-Series Forecasting (ARIMA Model)**.

  Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Machine Learning** (K-Means Clustering, ARIMA Time Series Forecasting)
- **Google Colab** (for execution)
- **GitHub** (for version control and sharing)

  📂 Dataset
The dataset contains **100 sample customer records** with the following columns:
- `customer_id` - Unique customer ID
- `recency` - Days since last purchase
- `frequency` - Total purchases made
- `monetary` - Total money spent
- `purchase_date` - Date of purchase
- `sales` - Sales amount

 🔹 Using a Real Dataset (Optional)
Instead of the generated dataset, you can use a real-world dataset from:
- [Kaggle E-commerce Datasets](https://www.kaggle.com/datasets)
- UCI Machine Learning Repository

 📊 Features Implemented
   1️⃣ Customer Segmentation (RFM + K-Means Clustering)
- **RFM Analysis** categorizes customers based on their purchasing behavior.
- **K-Means Clustering** groups customers into 3 segments:
  - High-value customers
  - Regular buyers
  - Inactive customers

 2️⃣ Sales Prediction (Time-Series Forecasting using ARIMA)
- **ARIMA Model** forecasts future sales based on historical data.
- **Visualization** of sales trends and predicted values.

   How to Run the Project
  Option 1: Google Colab (Recommended) 
1. Open the Jupyter Notebook (`customer_segmentation_sales.ipynb`) in Google Colab.
2. Run all cells to generate customer segmentation and sales prediction.
3. The dataset (`ecommerce_sales_data.csv`) will be created automatically.

 Option 2: Local Machine**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Ecommerce-Customer-Segmentation.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn statsmodels
   ```
3. Run the notebook in Jupyter:
   ```bash
   jupyter notebook
   ```

## 📌 Results
- **Customer Segments Identified** using clustering.
- **Sales Forecast** for the next 10 days visualized in a graph.

