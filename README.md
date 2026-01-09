# Soil-Diversity-Analysis
Exploratory Data Analysis (EDA) on soil microbial diversity using Python. Analyzing the effects of grazing, rainfall, and time on soil health



# Sensitivity Analysis of Soil Nutrient Pools & Microbial Diversity

## 📝 Project Description
This project explores the impact of environmental stressors and land management practices on soil health. Using a dataset of soil microbial communities, I analyzed how **Phylogenetic Diversity (faith_pd)** is influenced by grazing treatments, rainfall reduction, and geographical locations over a 5-year period (2018-2022). 

The goal is to understand which factors contribute most to the resilience of soil bacteria and fungi ecosystems.

## 🚀 Key Insights from Analysis
* **Grazing Impact:** 'Stable' grazing management supports the highest microbial diversity, while 'Destock' areas showed lower richness.
* **Microbial Types:** Bacterial communities exhibit higher phylogenetic diversity compared to fungal communities in this study area.
* **Climate Resilience:** Surprisingly, rainfall reduction showed a very weak correlation with diversity, suggesting the ecosystem is somewhat resilient to water stress.
* **Temporal Trends:** A significant decline in soil diversity was observed starting in 2020, highlighting potential long-term environmental shifts.

## 🛠️ Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy (Data Manipulation)
* **Visualization:** Matplotlib, Seaborn (Data Visualization)
* **Environment:** Jupyter Notebook

## 📊 Dataset Overview
The dataset includes variables such as:
- `site`: Location of study (FK or TB)
- `grazing_treatment`: Stable, Heavy, or Destock
- `rainfall_reduction`: Percentage of water reduction
- `faith_pd`: Measures of phylogenetic diversity
- `type`: Microbe category (Bacteria/Fungi)

## 📁 How to Run
1. Clone this repository.
2. Ensure you have Python installed.
3. Install dependencies: `pip install pandas seaborn matplotlib`
4. Run the Jupyter Notebook `Sensitivity_Soil_Nutrient_Pools Data Analysis.ipynb`.
