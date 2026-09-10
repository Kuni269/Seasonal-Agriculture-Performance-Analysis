# Seasonal Agriculture Performance Analysis

## Project Overview

Seasonal Agriculture Performance Analysis is a Data Analytics project that studies how agricultural performance changes across different seasons, crops, irrigation methods and economic conditions.

The project uses Python and Jupyter Notebook to clean, analyze and visualize an agriculture dataset. The analysis focuses on crop yield, production, profit, revenue, water usage, water efficiency and relationships between important agricultural variables.

## Problem Statement

Agricultural performance can vary because of seasonal conditions, farming practices, resource usage and market conditions. Raw agricultural data does not clearly show these differences.

This project analyzes the available agricultural dataset to identify meaningful patterns, trends, relationships and variations across crops and seasons.

## Objectives

- Analyze agricultural performance across Kharif, Rabi and Zaid seasons.
- Compare yield and production across different crops.
- Study profit and revenue patterns.
- Analyze irrigation methods and water usage.
- Compare water-use efficiency.
- Study relationships between yield and agricultural factors.
- Identify the best-performing crop and crop-season combinations.
- Provide data-driven observations and recommendations.

## Dataset

- 4,000 records
- 28 variables
- Seasons: Kharif, Rabi and Zaid

Important variables include crop, season, farm area, rainfall, temperature, humidity, soil conditions, nutrients, irrigation method, yield, production, market price, cost, revenue, profit, water usage, water efficiency and disease/pest risk.

## Technologies Used

- Python
- Pandas – data loading, cleaning and analysis
- NumPy – numerical processing
- Matplotlib – data visualization
- Seaborn – statistical visualization
- Jupyter Notebook – analysis and documentation

## Data Cleaning

The dataset was checked for missing values and duplicate records. Missing values were found in Rainfall, Soil Moisture and Yield. These numerical missing values were handled using median imputation. Duplicate records were also checked.

After cleaning, the dataset contained no missing values.

## Analysis Performed

1. **Seasonal Performance** – Average yield across Kharif, Rabi and Zaid.
2. **Crop-wise Analysis** – Comparison of crop yield and total production.
3. **Economic Analysis** – Profit and revenue by season and crop.
4. **Irrigation and Water Analysis** – Water usage and water-use efficiency by irrigation method.
5. **Correlation Analysis** – Relationships between yield and important agricultural variables.
6. **Crop + Season Analysis** – Comparison of crop performance across seasons.
7. **Overall Crop Performance** – Combined normalized score using profit, yield and water efficiency.

## Key Results

### Seasonal Yield

| Season | Average Yield (tonnes/ha) |
|---|---:|
| Kharif | 5.63 |
| Rabi | 5.04 |
| Zaid | 4.64 |

Kharif recorded the highest average yield.

### Seasonal Profit

| Season | Average Profit |
|---|---:|
| Kharif | ₹178,915 |
| Rabi | ₹87,689 |
| Zaid | -₹24,805 |

Kharif was the most profitable season overall.

### Best Crop

**Sugarcane** had the highest overall performance score when profit, yield and water efficiency were combined using the project's normalized scoring method.

### Best Crop-Season Combination

**Sugarcane – Kharif** had the highest average profit at approximately **₹10,00,791**.

**Chilli – Kharif** was the second-highest at approximately **₹9,54,380**.

### Correlation Findings

- Water efficiency ↔ Yield: **0.913**
- Production ↔ Yield: **0.883**
- Revenue ↔ Profit: **0.887**
- Rainfall ↔ Yield: **0.031**

Water efficiency shows a strong positive association with yield in this dataset, while rainfall alone has a very weak linear relationship with yield.

> Note: Correlation indicates association, not causation. The overall crop score is a project-defined comparison metric.

## Conclusion

The analysis shows that agricultural performance varies across crops and seasons. Kharif performs best overall in terms of average yield and profitability.

Sugarcane is the best-performing crop according to the combined performance score, and Sugarcane during Kharif is the strongest crop-season combination by average profit.

The results highlight the importance of water-use efficiency and provide useful comparisons of crop, season, irrigation and economic performance.

## Future Scope

- Build an interactive Power BI or Tableau dashboard.
- Add more years of historical agricultural data.
- Include weather forecasts and real-time environmental data.
- Develop machine-learning models for yield and profit prediction.
- Analyze regional and district-level differences in greater detail.
- Study irrigation practices and sustainability indicators.

## Project Files

```text
Seasonal-Agriculture-Performance-Analysis/
├── agricultural_analysis.ipynb
├── seasonal_agriculture_performance_dataset.csv
└── README.md
```

## How to Run

1. Install Python.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the project notebook.
5. Keep the CSV dataset in the same project folder.
6. Run the notebook cells from top to bottom.

## Author

**Kunal Rajesh Agrawal**  
**SVIT**

## GitHub Repository

Seasonal Agriculture Performance Analysis
