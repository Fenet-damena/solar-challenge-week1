# Solar Challenge – Week 1

This project is part of the Solar Challenge and focuses on data profiling, cleaning, exploratory data analysis (EDA), and cross-country comparison of solar energy datasets across different countries (Benin, Togo, Sierra Leone). The tasks are implemented in Python using Jupyter notebooks, Git, and GitHub Actions for CI/CD.

---

## 🔹 Task Summary

**Task 1:**  
- Initialized GitHub repository  
- Set up Python virtual environment  
- Created `.gitignore`, `requirements.txt`, and GitHub Actions CI workflow  
- Merged all setup changes into the `main` branch via Pull Request  

**Task 2:**  
- Loaded and profiled Benin’s solar dataset  
- Detected missing values and outliers  
- Imputed missing values and removed outliers using Z-score filtering  
- Exported cleaned dataset to `data/benin_clean.csv`  
- Created time series plots, correlation heatmaps, scatter plots, histograms, and a bubble chart  

**Task 3:**  
- Loaded cleaned datasets from Benin, Togo, and Sierra Leone  
- Combined datasets and labeled by country  
- Created boxplots for GHI, DNI, DHI metrics grouped by country  
- Computed summary table of mean, median, and standard deviation for each country  
- Performed one-way ANOVA test on GHI to assess statistical differences  
- Summarized key insights and ranked countries using a bar chart of average GHI  

---

## 🔹 Setup Instructions

### 📁 1. Clone the Repository
```bash
git clone https://github.com/Fenet-damena/solar-challenge-week1.git
cd solar-challenge-week1
