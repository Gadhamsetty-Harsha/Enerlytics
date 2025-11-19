# 🌍 Enerlytics - Global Energy Analysis

## 📌 Overview
Enerlytics analyzes global data related to energy consumption, production, emissions, GDP, and population. The dataset comes from the U.S. Energy Information Administration. SQL is used to study trends and compare countries.

## 🎯 Purpose
- Track global energy usage
- Study links between economic growth and energy output
- Compare countries using fair metrics
- Provide insights on sustainability and efficiency
  
## 🗂 Goals
- Organize global energy and economy data in SQL
- Study trends in consumption, production, and emissions
- Compare countries using ratios and per-capita metrics
- Understand links between GDP, energy use, and environmental impact

## 🛢 Dataset Structure
The data is stored in a relational SQL database with the following tables:
- Country
- Population
- Emission
- Consumption
- Production
- GDP
Each table stores yearly values for analysis.

## ⚠ Problem Statement
Countries try to grow their economies while reducing environmental impact. Large datasets make comparison difficult. This project solves the problem by:
- Structuring global energy and economy data
- Running SQL queries to find trends and correlations
- Studying per-capita values for fair comparisons
- Finding high and low performing countries
- Checking if countries move toward or away from sustainable energy use

## 📊 Analysis Covered
### 🔍 General and Comparative Analysis
- Total emissions by country
- Top five countries by GDP
- Production vs consumption by country and year
- High emission energy types

### 📆 Trend Analysis Over Time
- Yearly change in global emissions
- GDP trend for each country
- Population growth impact on emissions
- Changes in consumption for major economies
- Yearly change in emissions per capita

### 📈 Ratio and Per-Capita Analysis
- Emission to GDP ratio
- Consumption per capita
- Production per capita
- Countries with highest consumption relative to GDP
- Correlation between GDP growth and production growth

### 🌐 Global Comparisons
- Top ten countries by population and their emissions
- Countries with the largest fall in emissions per capita
- Global emission share by country
- Global averages of GDP, emissions, and population

## 💡 Key Insights
- A small number of countries contribute the largest share of emissions
- Coal, oil, and gas drive most emissions
- Some high-income countries show decreasing emission-to-GDP ratios
- Growing populations increase total emissions, but per-capita values vary
- High production does not always mean high consumption
- Better energy efficiency lowers emissions without reducing GDP growth

## 🛠 Tools Used
- SQL
- MySQL or PostgreSQL
- ER model design
- Visualization tools for charts (Tableau, Power BI, Matplotlib)

## 🚀 How to Run
1. Install MySQL or PostgreSQL
Install MySQL or PostgreSQL.

2. Create a database
Set up a new database.

3. Import all table scripts
Load table and insert scripts.

4. Run the analysis queries
Execute queries from queries.sql.

5. View results and charts
Open charts from the visuals folder.

## 🤝 Contributing
- Fork the repository
- Create a branch
- Commit changes
- Open a pull request

---
Enerlytics = Energy + Analytics ♻🔋💡
