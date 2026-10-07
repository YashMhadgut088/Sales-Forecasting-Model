# 📈 Sales Forecasting Model Using AI & Python

## 📌 Project Overview

This project focuses on building a **Sales Forecasting Model using Python and Prophet** to predict future sales based on historical sales data.

The project analyzes historical store sales, identifies sales trends over time, and generates future sales forecasts.

## 🎯 Objectives

- Analyze historical sales data
- Understand sales trends over time
- Perform data preprocessing and exploratory data analysis
- Aggregate sales on a daily basis
- Build a time-series forecasting model
- Predict future sales
- Export forecasted results into a CSV file

## 📊 Dataset

The project uses a sales dataset containing **3,000,888 records and 6 columns**.

### Main Features

| Column | Description |
|---|---|
| `id` | Unique record identifier |
| `date` | Sales date |
| `store_nbr` | Store number |
| `family` | Product category |
| `sales` | Sales value |
| `onpromotion` | Number of products on promotion |

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Prophet
- Scikit-learn

## 🔄 Project Workflow

1. Install and import required libraries
2. Load the sales dataset
3. Inspect dataset structure and information
4. Convert the date column into datetime format
5. Perform Exploratory Data Analysis
6. Aggregate sales on a daily basis
7. Visualize sales trends
8. Prepare data for forecasting
9. Build the Prophet forecasting model
10. Generate future sales predictions
11. Visualize the forecast
12. Export forecast results to CSV

## 🤖 Forecasting Model

### Prophet

The project uses **Prophet**, a time-series forecasting model, to identify patterns in historical sales data and predict future sales.

Prophet is suitable for this project because the data contains a date-based sales history and the objective is to forecast future values.

## 📈 Data Visualization

The project includes visualization of:

- Daily sales trends
- Historical sales patterns
- Forecasted sales
- Future sales predictions

These visualizations help understand how sales change over time and provide insights into expected future sales.

## 📁 Project Structure

```text
Sales-Forecasting-Model/
│
├── Sales Forecasting Model.ipynb
├── train.csv
├── forecast_output.csv
└── README.md
```

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Sales-Forecasting-Model.git
```

### 2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn prophet scikit-learn
```

### 3. Open the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Sales Forecasting Model.ipynb
```

### 4. Run the notebook

Run the cells step-by-step to load the dataset, analyze sales trends, build the forecasting model, and generate predictions.

## 📤 Output

The forecast results are exported into:

```text
forecast_output.csv
```

This file contains the generated sales forecast results.

## 🔮 Future Improvements

- Add more external features such as holidays and promotions
- Compare Prophet with other forecasting models
- Improve forecasting accuracy
- Build an interactive dashboard using Power BI or Streamlit
- Deploy the forecasting model as a web application

## 👨‍💻 Author

**Yash Mhadgut**

Bachelor of Data Science  
University of Mumbai

### Skills Demonstrated

`Python` `Pandas` `NumPy` `Data Analysis` `EDA` `Data Visualization` `Time Series Forecasting` `Prophet` `Machine Learning`
