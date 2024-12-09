# 🚗 Mercedes-Benz Vehicle Data Analysis

This project involves the analysis and visualization of a Mercedes-Benz vehicle dataset. The analysis focuses on vehicle prices, production years, mileage, engine size, and other features. The goal is to extract insights and identify patterns in the data. 📊

---

## 🗂️ Project Content

### 📚 Libraries Used
- **pandas**: Data manipulation and analysis 📑  
- **numpy**: Numerical operations ➕➖  
- **matplotlib**: Plotting and visualization 📈  
- **seaborn**: Advanced data visualization 🎨  

### 📁 Dataset
**File Name:** `merc.xlsx`  
The dataset consists of **13,119 rows** and **7 columns**:
- **year**: Production year of the vehicle 📆  
- **price**: Price of the vehicle 💰  
- **transmission**: Type of transmission (Automatic, Manual, etc.) ⚙️  
- **mileage**: Vehicle mileage 🛣️  
- **tax**: Tax amount 💸  
- **mpg**: Miles per gallon ⛽  
- **engineSize**: Engine size 🔧  

### 🛠️ Data Preprocessing
- ✅ Column names were translated into English.  
- ✅ Missing data analysis revealed no null values.  
- ✅ Data types and statistical summaries were inspected.  

---

## 📊 Visualizations

### 🖼️ Sample Visuals

1. **Transmission Types Distribution (Pie Chart)** 🍰  
   ![Transmission Distribution](./images/transmission_distribution.png)

2. **Price Trend Analysis (Line Chart)** 📉  
   ![Price Trend Analysis](./images/price_trend_analysis.png)

3. **Vehicle Count by Year (Bar Chart)** 📊  
   ![Vehicle Count by Year](./images/vehicle_count_by_year.png)

4. **Average Prices by Year (Bar Chart)** 💲  
   ![Average Prices by Year](./images/average_prices_by_year.png)

---

## 🔍 Key Findings
- **Transmission Types:** "Semi-Auto" is the most common transmission type. ⚙️  
- **Price Trends:** Vehicles from 2019 and 2020 tend to have higher prices compared to other years. 💰  
- **Mileage vs. Price:** Lower mileage generally correlates with higher prices. 🛣️  

---

## 🚀 How to Run
1. Place the `merc.xlsx` file in the working directory. 📂  
2. Run the script in a Python environment:  
    ```bash
    python CarAnalysis.py
    ```
3. Output visuals will be saved in the `images` folder. 🖼️  

