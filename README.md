# 🧫 Tuberculosis (TB) Data Analysis

This project explores the global spread and trends of tuberculosis (TB) using two comprehensive Kaggle datasets. It aims to identify patterns, compare regional impacts, and highlight key indicators related to TB incidence and mortality.

## 📦 Datasets Used

1. **[Determine the Pattern of Tuberculosis Spread](https://www.kaggle.com/datasets/henajose/determine-the-pattern-of-tuberculosis-spread)**  
   Contains historical data on TB cases across countries, including year-wise trends and suspected/confirmed classifications.

2. **[WHO TB Dataset (2024-03-21)](https://www.kaggle.com/datasets/chibuzornwachukwu/who-tb-datasets?select=WHO+TB+dataset_2024-03-21.xlsx)**  
   Official WHO data with detailed estimates on incidence, mortality (with and without HIV), treatment success, and healthcare indicators up to 2024.

## 🎯 Objectives

- Analyze global and regional TB trends over time
- Identify countries with the highest TB burden
- Compare TB mortality with and without HIV
- Provide visual insights for public health awareness

## 🧪 Methodology

- **Data Cleaning & Merging**: Handle missing values, align country/year references across datasets
- **Exploratory Data Analysis (EDA)**: Use statistical summaries and group-by aggregation
- **Visualization**: Create plots and charts to visualize trends and regional comparisons

## 📊 Sample Visualizations

- 📉 Estimated TB mortality (excluding HIV) over time
- 🌍 TB incidence heatmap by country
- 📊 ASEAN vs Global mortality rate comparison

## 🛠 Technologies Used

- Python 3.x  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook / Google Colab

## 📂 Project Structure

```bash
├── datasets/
│   ├── tb_pattern.csv
│   └── WHO_TB_dataset_2024.xlsx
├── notebooks/
│   └── tb_analysis.ipynb
├── visuals/
│   ├── global_trend.png
│   ├── asean_vs_global.png
├── README.md
