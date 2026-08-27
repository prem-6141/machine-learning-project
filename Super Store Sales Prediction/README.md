# 🛒 Super Store Sales Prediction

## 📌 Project Overview

**Super Store Sales Prediction** is a Machine Learning project that predicts future sales based on historical sales data.

The project analyzes factors such as **order date, sales, quantity, discount, profit, category, sub-category, region, and customer details** to identify sales patterns and make predictions.

This project can help businesses understand their sales performance and make better decisions about inventory, marketing, and business planning.

## 🎯 Objectives

* Predict future sales using Machine Learning.
* Analyze historical sales data.
* Identify important factors affecting sales.
* Understand sales and profit trends.
* Help businesses make data-driven decisions.
* Visualize sales performance through charts and graphs.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Streamlit**
* **Jupyter Notebook / VS Code**

## 📂 Project Structure

```text
Super-Store-Sales-Prediction/
│
├── dataset.csv
├── sales_prediction.ipynb
├── model.pkl
├── app.py
├── requirements.txt
└── README.md
```

## 📊 Dataset

The dataset contains historical Super Store sales information, including:

* Order Date
* Ship Date
* Customer Name
* Segment
* Country
* City
* State
* Region
* Category
* Sub-Category
* Sales
* Quantity
* Discount
* Profit

## 🔄 Project Workflow

```text
Historical Sales Data
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Data Preprocessing
        ↓
Train-Test Split
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Sales Prediction
        ↓
Visualization / Dashboard
```

## 🤖 Machine Learning

The project can use regression algorithms such as:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor

The model can be evaluated using:

* **MAE** – Mean Absolute Error
* **MSE** – Mean Squared Error
* **RMSE** – Root Mean Squared Error
* **R² Score** – Coefficient of Determination

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/prem-6141/Super-Store-Sales-Prediction.git
```

### 2. Open the Project

```bash
cd Super-Store-Sales-Prediction
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
sales_prediction.ipynb
```

### 5. Run the Streamlit Application

```bash
streamlit run app.py
```

The application will open in your browser.

## 💡 Key Features

* 📊 Historical sales analysis
* 📈 Sales trend visualization
* 💰 Profit analysis
* 🛍️ Category and sub-category analysis
* 🌎 Regional sales analysis
* 🤖 Machine Learning-based sales prediction
* 📉 Interactive dashboard
* 🔮 Future sales forecasting

## 📈 Example Prediction

```text
Input:
Category       : Technology
Quantity       : 5
Discount       : 10%
Region         : West

Output:
Predicted Sales: ₹/ $ XXXX
```

*The actual output depends on the dataset and trained model.*

## 📌 Applications

* Retail business analysis
* Sales forecasting
* Inventory planning
* Business decision-making
* Customer and product analysis
* Profit optimization

## 🔮 Future Scope

* Implement advanced time-series forecasting.
* Add real-time sales data.
* Deploy the application on cloud platforms.
* Add automated sales reports.
* Predict profit along with sales.
* Add inventory demand prediction.
* Use advanced models such as XGBoost and LSTM.
* Create a real-time business intelligence dashboard.

## 👨‍💻 Author

**Prem Bagal**

## 📜 License

This project is created for **educational and academic purposes**.
