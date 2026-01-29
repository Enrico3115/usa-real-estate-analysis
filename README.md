# 🏠 USA Real Estate Market Analysis

An Exploratory Data Analysis (EDA) of the USA real estate market, analyzing over 2 million housing listings. This project applies data visualization principles to uncover market trends, price distributions, and historical value changes.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)

## 📊 Project Overview
This project focuses on visualizing complex real estate data to answer key questions about the US housing market. It serves as a practical application of **Chapter 3 (Visualizing Data)** from the book *"Data Science from Scratch"* by Joel Grus, adapted for a large-scale real-world dataset.

**Key Analyses Performed:**
* **Geographic Hotspots:** Identified top 5 states by transaction volume.
* **Price Distributions:** Analyzed property sizes and price skewness (Mean vs. Median).
* **Market Dynamics:** Visualized the correlation between Size (sqft) and Price in major metro areas (Boston).
* **Historical Trends:** Tracked average housing prices from 1900 to 2025 to visualize long-term market appreciation.

## 📂 Dataset
The dataset used is the **USA Real Estate Dataset** from Kaggle.
* **Source:** [Kaggle - USA Real Estate Dataset](https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset)
* **Size:** ~2.2 million records
* **Features:** Price, Size (sqft), State, City, Previous Sold Date.

## 🛠️ Technologies Used
* **Python**: Core programming language.
* **Pandas**: For efficient data manipulation and cleaning of large datasets (2M+ rows).
* **Matplotlib**: For creating static, publication-quality visualizations (Histograms, Scatter Plots, Bar Charts).
* **NumPy**: For numerical operations.

## 📈 Key Findings
1.  **Market Concentration:** The housing market volume is heavily concentrated in specific states.
2.  **Right-Skewed Distribution:** House sizes and prices follow a right-skewed distribution, where the **Mean** is significantly higher than the **Median** due to luxury outliers.
3.  **Appreciation Trend:** The historical time-series analysis reveals a consistent exponential growth in average housing prices over the last century.

## 🚀 How to Run
1.  Clone this repository:
    ```bash
    git clone [https://github.com/Enrico3115/usa-real-estate-analysis.git](https://github.com/Enrico3115/usa-real-estate-analysis.git)
    ```
2.  Install required packages:
    ```bash
    pip install pandas matplotlib numpy
    ```
3.  Download the dataset from Kaggle and place `realtor-data.zip.csv` in the root folder.
4.  Run the notebook `data_visualization.ipynb`.

---
*This project was created as part of my journey through "Data Science from Scratch".*
