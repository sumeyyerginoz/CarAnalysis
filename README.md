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

1. **Transmission Types Distribution**  
<img width="234" alt="Ekran Resmi 2024-12-10 11 34 07" src="https://github.com/user-attachments/assets/53967d0d-aff3-4a38-9214-15940578f9e8">

2. **Price Trend Analysis**
<img width="642" alt="Ekran Resmi 2024-12-10 11 34 38" src="https://github.com/user-attachments/assets/0861d3a3-d58e-4c19-9cec-e1847e8b653c">

3. **Vehicle Price by Year (Bar Chart)**  
<img width="425" alt="Ekran Resmi 2024-12-10 11 38 38" src="https://github.com/user-attachments/assets/a86df5d1-eff5-4d74-8db7-c20badf10330">


4. **Average Prices by Year (Bar Chart)**
<img width="401" alt="Ekran Resmi 2024-12-10 11 35 32" src="https://github.com/user-attachments/assets/7da9fd4c-b8d5-4eb9-ad06-6c8b265b9176">
<br>
<img width="411" alt="Ekran Resmi 2024-12-10 11 39 41" src="https://github.com/user-attachments/assets/75e17b33-406b-4bf6-b3b4-0f5f11375f41">
<img width="422" alt="Ekran Resmi 2024-12-10 11 39 57" src="https://github.com/user-attachments/assets/78ca700c-4472-43ab-91ae-601146238ee7">
<img width="619" alt="Ekran Resmi 2024-12-10 11 40 22" src="https://github.com/user-attachments/assets/e9ec6580-0d90-45fc-9a38-60bfcbe8c4b5">

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

