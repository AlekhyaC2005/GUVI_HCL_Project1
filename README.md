# GUVI_HCL_Project1

# 🌍 COVID-19 Data Analysis & Dashboard

This project performs an exploratory data analysis (EDA) and visualization of COVID-19 cases across different countries using Python and Power BI. It highlights key trends such as active cases, recovery rates, and death rates using a global dataset.

---

## 📁 Repository Structure

.
├── covid19_dashboard.png # Power BI dashboard screenshot
├── full_grouped.csv # Original dataset
├── covid.csv # Cleaned version of dataset
├── covid_analysis.ipynb # Python Jupyter Notebook
├── main.py # Optional Python script
├── README.md # Project documentation


---

## 🧠 Objective

- Analyze global trends in COVID-19 infections, recoveries, and deaths.
- Visualize the insights using Matplotlib, Seaborn, and Power BI.
- Practice data cleaning, grouping, aggregation, and model deployment (optional).

---

## 📊 Dataset Information

- **File Name:** `full_grouped.csv`
- **Source:** Public COVID-19 datasets (e.g., Johns Hopkins, Kaggle)
- **Columns:** `Country/Region`, `Date`, `Confirmed`, `Deaths`, `Recovered`, `Active`, etc.
- **Timeframe:** Data spans from early pandemic (2020) to around 2021

---

## 🔧 Requirements

Install required Python packages:

bash
pip install pandas matplotlib seaborn 

🚀 How to Run the Project
Step 1: Clone the Repository

git clone [https://github.com/yourusername/covid19-dashboard.git](https://github.com/AlekhyaC2005/GUVI_HCL_Project1.git)
cd covid19-dashboard

Step 2: Run Python Notebook

Use Jupyter or any IDE:
jupyter notebook covid_analysis.ipynb

OR run the .py file if provided:

python main.py

Step 3: View the Power BI Dashboard
Open covid19_dashboard.png (static image)
If you have the .pbix file, open it in Power BI Desktop for full interactivity.

📈 Visualizations Created
✅ Using Python
Line Chart: Active cases over time

Bar Chart: Top 30 countries by active cases

Pie Chart: Recovery vs Death distribution

Statistical Overview: Nulls, duplicates, mean, etc.

✅ Using Power BI
Interactive dashboards for:

Total Confirmed/Deaths/Recovered cases

Country-wise filters and time-based slicers




