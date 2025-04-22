# QTM350_final_project

# Long-Term Development Indicators and Global Trends

This repository contains the final project for the course, focusing on analyzing long-term development trends across countries using data from the World Bank's World Development Indicators (WDI). The study investigates relationships between life expectancy, fertility rate, population growth, and school enrollment from 1960 to 2023.

---

## Group Members

- Jacky An 
- Bernice  
- Eric  

---

## Research Questions

1. How has life expectancy evolved globally since 1960, and how is it associated with fertility and education trends?  
2. What is the relationship between school enrollment and fertility rate across countries?  
3. Do countries with rapid population growth face distinct development challenges in terms of life expectancy?  
4. What insights can we derive from multivariable regression models that predict life expectancy using demographic and education indicators?

---

## Project Overview

This project leverages real-world data from the **World Bank’s World Development Indicators (WDI)** database. We focus on four key development indicators that reflect demographic and human capital trends:

- **Life Expectancy at Birth (SP.DYN.LE00.IN)**  
- **Fertility Rate (SP.DYN.TFRT.IN)**  
- **Population Growth (SP.POP.GROW)**  
- **School Enrollment, Primary (% gross) (SE.PRM.ENRR)**

By analyzing these indicators across over 100 countries and more than six decades, we aim to uncover patterns that reveal how improvements in healthcare, education, and demographic shifts are linked to long-term development outcomes.

---

## Repository Structure

1. **data**  
   Contains the original and cleaned datasets used in this project.

2. **scripts**  
   - `data_analysis.py`: Main script for data wrangling, statistical analysis, and visualization.  
   - `regression_models.py`: Supplementary script for running regression models predicting life expectancy.

3. **figures**  
   Stores all generated plots and visualizations used in the final report.

4. **report**  
   - `report.qmd` and `report.html`: Final compiled report containing narrative explanations, plots, and statistical results.

5. **documentation**  
   - `codebook.md`: Descriptions of all variables used in the dataset.

---

## Reproducing the Project

To replicate our results and analysis:

1. **Download the Repository**  
   Clone or download this GitHub repository to your local machine.

2. **Install Dependencies**  
   Required Python libraries include: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, and `quarto`.

3. **Run the Analysis**  
   - Open and execute `scripts/data_analysis.py` to reproduce data cleaning, visualization, and correlation analyses.  
   - Optionally run `regression_models.py` for the statistical modeling portion.

4. **View the Report**  
   Open the compiled `report.html` or `report.qmd` file under the `report/` folder to explore our full findings, visualizations, and conclusions.

---

## Technologies Used

- **Python**: Data cleaning, analysis, regression modeling  
- **Pandas & NumPy**: Data manipulation and transformation  
- **Matplotlib & Seaborn**: Data visualization  
- **Statsmodels**: Statistical modeling  
- **Quarto**: Report generation and formatting  

---

## Acknowledgments

We thank the **World Bank** for providing access to the WDI database and credit our course instructor **Danilo Freire**!!!
