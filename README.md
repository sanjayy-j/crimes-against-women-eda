# Crimes Against Women in India – Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) of crimes against women in India, conducted as part of the TAM-VIT recruitment task. The objective is to analyze state-wise crime patterns, identify dominant crime types, and cluster states based on crime statistics.

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
