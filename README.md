# Task_05_Descriptive_Stats

In this project, I combined three datasets – the 2021 World Happiness Report, the 2021 Women’s Happiness Report (with country, rank, and score), and map data with subregions and country codes.
The goal was to analyze which factors (GDP, social support, health, etc.) drive women’s happiness across countries.
The map data was included to enable deeper regional analysis and future interactive visualizations (e.g., using Plotly).
ments of well-being can be used effectively to assess the progress of nations. The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness.

## Steps Performed

1. **Data Cleaning & Merging**
   - Selected relevant columns.
   - Standardized column names and merged 3 datasets on `Country`.
   - Final dataset has 125 countries and 11 features.

2. **Exploratory Data Analysis (EDA)**
   - Checked distributions of numeric and categorical features.
   - Plotted histograms, bar plots, and scatter plots.
   - Built a correlation heatmap and identified key factors related to Score.

3. **Question-Based Analysis**
   - Created 11 natural language questions (simple to complex).
   - Computed answers using Python (ground truth).

4. **LLM Evaluation**
   - Asked the same 11 questions to ChatGPT using the cleaned dataset.
   - Compared LLM answers to ground truth.

---

## Key Findings

- **Top factors driving women’s happiness:**  
  `Healthy life expectancy`, `GDP`, and `Social support`.

- **Negative factor:**  
  `Perceptions of corruption` (higher corruption is linked to lower happiness).

- **Top sub-region:**  
  Western Europe had the highest average Score.

- **LLM Performance:**  
  ChatGPT answered all 11 questions correctly, matching the ground truth perfectly.

**Conclusion:**

This project combined women’s happiness scores with global happiness indicators to understand which factors most influence well-being across countries. Through data cleaning, merging, and exploratory analysis, we found that healthy life expectancy, GDP, and social support are the strongest drivers of women’s happiness, while perceptions of corruption have a strong negative impact. After generating and answering 11 structured questions using Python, we compared the results with ChatGPT’s analysis on the same dataset. The LLM accurately matched all ground-truth answers, showing strong potential for supporting data-driven insights when given clean, well-structured data.



