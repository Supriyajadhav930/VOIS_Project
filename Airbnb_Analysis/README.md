# 🏡 Airbnb Hotel Booking Data Analysis

## 📌 Project Overview

The **Airbnb Hotel Booking Data Analysis** project focuses on exploring Airbnb listing data to understand pricing patterns, room types, guest reviews, host performance, and listing availability.

Using Python, Pandas, NumPy, Matplotlib, and Seaborn, this project performs data cleaning, preprocessing, Exploratory Data Analysis (EDA), and data visualization to discover meaningful insights from Airbnb data.

## 🎯 Project Objectives

- Analyze Airbnb prices across different room types.
- Compare average listing prices across neighbourhood groups.
- Study guest reviews and room type performance.
- Analyze guest demand using monthly reviews.
- Identify the top 10 hosts based on total reviews.
- Compare listing availability across different room types.
- Understand listing performance across neighbourhood groups.

## 📂 Dataset Description

The dataset contains **102,599 records and 26 columns** before preprocessing.

It includes information about:

| Category | Features |
|---|---|
| Listing Details | ID, Name, Room Type |
| Host Information | Host ID, Host Name, Identity Verification |
| Location | Country, Neighbourhood Group, Neighbourhood, Latitude, Longitude |
| Pricing | Price, Service Fee |
| Reviews | Number of Reviews, Reviews per Month, Review Rate |
| Availability | Availability 365, Minimum Nights |
| Other Information | Cancellation Policy, Construction Year, House Rules |

**Dataset File:** `Airbnb_Open_Data.xlsx`

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Jupyter Notebook** – Development environment
- **VS Code** – Code editor

## 🔍 Project Workflow

### 1. Data Loading and Exploration

- Imported the dataset using Pandas.
- Examined the first and last records.
- Checked dataset shape and column names.
- Analyzed data types and statistical summaries.
- Identified duplicate records and missing values.

### 2. Data Cleaning and Preprocessing

- Identified 541 duplicate records and removed them.
- Handled missing categorical values using mode imputation.
- Replaced missing listing and host names with "Unknown".
- Handled missing numerical values using median imputation.
- Replaced missing monthly review values with zero.
- Replaced missing house rules with "Not Available".
- Converted price and service fee columns into numerical formats.
- Removed the license column due to extensive missing values.
- Checked missing values after preprocessing.

### 3. Outlier Detection

Used the **Interquartile Range (IQR) method** to identify potential outliers in numerical columns.

The analysis examined:
- Latitude and Longitude
- Construction Year
- Minimum Nights
- Number of Reviews
- Review Rate Number
- Calculated Host Listings Count
- Availability 365

### 4. Exploratory Data Analysis (EDA)

Performed analysis to answer questions such as:

- Which room type has the highest average price?
- Which neighbourhood group has higher average listing prices?
- Which room type receives more guest reviews?
- Which room type has higher monthly reviews?
- Who are the top 10 hosts based on total reviews?
- Which room type has higher yearly availability?
- How does listing performance vary across neighbourhood groups?

## 📊 Data Visualizations

Created different visualizations using Matplotlib and Seaborn:

- Bar Plot – Average Price by Room Type.
- Bar Plot – Average Airbnb Price by Neighbourhood Group.
- Bar Plot – Average Number of Reviews by Room Type.
- Bar Plot – Guest Demand by Room Type.
- Horizontal Bar Plot – Top 10 Hosts by Number of Reviews.
- Bar Plot – Average Listing Availability by Room Type.
- Bar Plot – Location Performance by Neighbourhood Group.

## 💡 Key Findings

Based on the analysis performed in the notebook:

- Hotel rooms recorded the highest average price among the room types, approximately 666.39.
- Queens recorded the highest average price among the consistently named neighbourhood groups, approximately 630.20.
- Hotel rooms had the highest average number of reviews, approximately 84.08.
- Hotel rooms also recorded the highest average monthly reviews, approximately 2.87.
- Michael was the top host by total number of reviews, with 24,612 reviews.
- Hotel rooms had the highest average availability, approximately 219.93 days.

**Data Quality Observation:** Some neighbourhood group names have inconsistent spellings, such as "brookln" and "manhatan". These are separate categories in the current analysis and may affect location comparisons.

## 🎯 Conclusion

This project demonstrates how Python-based data analysis can be used to explore Airbnb listing data and identify patterns related to pricing, room types, guest reviews, host performance, and availability.

Through data cleaning, preprocessing, exploratory data analysis, and visualization, the project provides a better understanding of different aspects of Airbnb listings.

The analysis helped develop practical skills in data manipulation, handling missing values, outlier detection, grouping, statistical analysis, and data visualization.

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/Supriyajadhav930/VOIS_Project.git
   ```

2. Navigate to the Airbnb project folder:

   ```bash
   cd VOIS_Project/Airbnb_Analysis
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl jupyter
   ```

4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Airbnb_Hotel_Booking.ipynb` and run the notebook cells.

## 👩‍💻 Author

**Supriya Jadhav**

B.Tech – Information Technology

**Skills:** Python, Data Analysis, Data Cleaning, Exploratory Data Analysis (EDA), Data Visualization, Pandas, NumPy.
