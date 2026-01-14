# Crimes Against Women in India – Exploratory Data Analysis (EDA)

> A real-world exploratory analysis of public safety data using Python and data visualization techniques.

This project presents a structured Exploratory Data Analysis (EDA) of crimes against women in India using officially reported state-wise crime data. The analysis focuses on uncovering patterns, trends, and regional disparities across different categories of gender-based violence.

The objective of this project is to demonstrate a real-world data analysis workflow, including data cleaning, aggregation, visualization, and interpretation of insights. By examining crime distributions across states and crime types, the project highlights how data-driven analysis can support awareness, policy discussion, and targeted interventions in public safety and social impact domains.

This repository is designed to be domain-agnostic and reusable, showcasing practical data analysis skills applicable to large-scale social, governance, and public-sector datasets.


---

## 📌 Objectives

- Identify states with the highest reported crimes against women
- Analyze crime distribution by crime type
- Cluster states based on crime patterns
- Visualize trends using bar charts, heatmaps, and cluster plots
- Derive meaningful insights from the data (no ML prediction involved)

---

## 📊 Dataset

- **CrimesOnWomenData.csv** – State-wise crime statistics  
- **description.csv** – Explanation of dataset columns  

The dataset includes multiple crime categories such as assault, kidnapping, domestic violence, and other offenses against women across Indian states.

---

## 🛠 Tech Stack

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment:** Google Colab / Jupyter Notebook  

---

## 🔍 Analysis Performed

### 1. State-wise Crime Analysis
Identified top states with the highest reported crimes against women using aggregated totals.

### 2. Crime Type Distribution
Analyzed which categories of crimes contribute the most to overall crime statistics.

### 3. Correlation Analysis
Used heatmaps to understand relationships between different crime types.

### 4. Clustering of States
Applied K-Means clustering to group states based on similar crime patterns.

---

## 📈 Visualizations

- Bar chart of top states by crime count  
- Bar chart of crimes by type  
- Correlation heatmap of crime categories  
- Scatter plot showing clustered states  

All plots are saved in the `visuals/` directory.

---

## 🧠 Key Insights

- A small number of states account for a significant portion of reported crimes.
- Domestic violence-related offenses dominate the dataset.
- Several crime types are positively correlated, indicating interconnected social issues.
- States can be grouped into high, medium, and low crime clusters, useful for targeted policy interventions.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sanjayy-j/crimes-against-women-eda.git
