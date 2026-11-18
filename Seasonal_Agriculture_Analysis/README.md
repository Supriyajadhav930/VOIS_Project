# 🌾 Seasonal Agriculture Performance Analysis

## 📌 Project Overview

The **Seasonal Agriculture Performance Analysis** project focuses on analyzing agricultural data to understand how farming performance varies across different seasons.

The project explores the relationship between seasonal weather conditions, soil characteristics, crop production, yield, water consumption, and economic outcomes.

Using Python and data visualization techniques, this project aims to identify seasonal patterns and generate insights that can support better agricultural planning and resource management.

## 🎯 Project Objectives

- Analyze agricultural performance across different seasons.
- Compare crop production and yield across Kharif, Rabi, and Zaid seasons.
- Study the impact of rainfall, temperature, humidity, and soil moisture.
- Analyze water consumption and water efficiency.
- Compare agricultural profit across seasons.
- Understand variations in disease and pest risk.
- Explore differences in crop yield across states.

## 📂 Dataset Description

The dataset contains **4,000 records and 28 columns** related to agricultural performance.

The dataset includes the following categories:

| Category | Features |
|---|---|
| Location | State, District |
| Crop Information | Crop, Season, Farm Area |
| Weather Conditions | Rainfall, Temperature, Humidity, Sunlight |
| Soil Characteristics | Soil pH, Soil Moisture |
| Agricultural Resources | Nitrogen, Phosphorus, Potassium, Fertilizer |
| Production | Crop Yield, Production |
| Economic Factors | Market Price, Total Cost, Revenue, Profit |
| Water Management | Water Used, Water Efficiency |
| Risk Analysis | Disease and Pest Risk |

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Jupyter Notebook** – Development environment

## 🔍 Project Workflow

### 1. Data Loading and Exploration
- Imported the dataset using Pandas.
- Examined the first and last records.
- Checked dataset dimensions, column names, and data types.
- Used descriptive statistics to understand numerical features.

### 2. Data Cleaning and Preprocessing
- Checked for duplicate records.
- Identified missing values.
- Filled missing values in `Rainfall_mm` and `Soil_Moisture_pct` using median imputation.
- Removed remaining rows containing missing values.
- Final cleaned dataset: **3,968 records and 28 columns**.

### 3. Outlier Detection
- Used the Interquartile Range (IQR) method.
- Calculated Q1, Q3, IQR, lower bounds, and upper bounds.
- Identified potential outliers in numerical columns.

### 4. Exploratory Data Analysis (EDA)

Performed analysis to answer questions such as:

- How does agricultural performance vary across seasons?
- Which season has higher average crop yield?
- How do weather conditions change across seasons?
- How does water usage vary between seasons?
- Is there a relationship between rainfall and crop yield?
- How do agricultural profits differ across seasons?
- How does crop yield vary across states?
- How does disease and pest risk change across seasons?

## 📊 Data Visualizations

The project uses different visualizations to understand agricultural patterns:

- Bar Plot – Average crop production across seasons.
- Line Plot – Seasonal patterns in average crop yield.
- Heatmap – Agricultural characteristics across seasons.
- Count Plot – Crop distribution across seasons.
- Bar Plot – Average water usage across seasons.
- Scatter Plot – Rainfall vs. crop yield.
- Bar Plot – Average profit across seasons.
- Grouped Bar Plot – Average yield across states and seasons.
- Box Plot – Disease and pest risk across seasons.
- Heatmap – Overall seasonal agricultural performance.
- Scatter Plot – Water efficiency vs. crop yield.

## 💡 Key Findings

Based on the observations recorded in the notebook:

- Kharif recorded the highest average yield and production.
- Rabi showed lower average production.
- Water usage varied across seasons, indicating differences in resource requirements.

These observations demonstrate the importance of considering seasonal variations when analyzing agricultural performance.

## 🎯 Conclusion

This project demonstrates how data analysis and visualization can help understand agricultural performance across different seasons.

By examining environmental conditions, crop yield, production, water usage, and economic factors, the analysis provides insights into seasonal agricultural patterns.

The findings can support better seasonal agricultural planning and more informed resource management decisions.

## ▶️ How to Run the Project

1. Clone this repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Navigate to the project folder:

   ```bash
   cd Seasonal_Agriculture_Analysis
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Seasonal_Agriculture_Performance_Analysis.ipynb` and run the cells.

## 👩‍💻 Author

**Supriya Jadhav**

B.Tech – Information Technology

**Skills:** Python, Data Analysis, Data Cleaning, Exploratory Data Analysis (EDA), Data Visualization.
