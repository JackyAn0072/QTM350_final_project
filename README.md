# QTM350 Final Project: Long-Term Development Indicators and Global Trends

Welcome to our final project repository for **QTM 350: Data Science for Public Policy** at Emory University!  
In this project, we explore **how demographic and education indicators are associated with development outcomes over time** using real-world data from the **World Bank's World Development Indicators (WDI)** from **1960 to 2023**.

---

## 📚 Project Description

This study investigates the long-term relationships among four key global development indicators:

- **Life Expectancy at Birth** (`SP.DYN.LE00.IN`)  
- **Fertility Rate** (`SP.DYN.TFRT.IN`)  
- **Population Growth** (`SP.POP.GROW`)  
- **Primary School Enrollment, Gross (%)** (`SE.PRM.ENRR`)  

By analyzing these indicators across more than **100 countries** over **six decades**, we aim to answer important questions about health, education, and demographic transitions worldwide.  
Our approach combines **descriptive analysis**, **visualization**, and **multivariable regression modeling** to uncover significant patterns and predictors of development.

---

## 🔍 Research Questions

1. **Global Trends**: How has life expectancy evolved globally since 1960, and how does it relate to changes in fertility and education?
2. **Education and Fertility**: What is the relationship between school enrollment rates and fertility rates across countries and regions?
3. **Population Growth and Challenges**: Do countries with faster population growth experience different development patterns in terms of life expectancy?
4. **Predictive Modeling**: Can we accurately predict life expectancy using fertility rates, school enrollment, and population growth rates?

---

## 🏗️ Repository Structure

```
QTM350_final_project/
├── datasets/         # Raw and processed data files
├── figures/          # Generated plots and backup visualizations
├── scripts/          # Python scripts for analysis and modeling
│   ├── data_analysis.py
│   └── regression_models.py
├── report/           # Final report files (.qmd and .html)
├── README.md         # Project overview (this file)
└── requirements.txt  # (optional) list of dependencies
```

- **datasets/**: Contains the downloaded World Bank WDI dataset used for analysis.
- **scripts/**: 
  - `data_analysis.py`: Prepares the data, creates descriptive statistics, and visualizes key relationships.
  - `regression_models.py`: Runs multivariable regression models predicting life expectancy.
- **figures/**: Backup storage for generated plots, including trendlines and regression plots.
- **report/**:
  - `report.qmd`: Quarto markdown source for the final report.
  - `report.html`: Rendered full report with narratives, visualizations, and findings.

---

## 🖥️ How to Reproduce Our Analysis

### 1. Clone the Repository

```bash
git clone https://github.com/JackyAn0072/QTM350_final_project.git
cd QTM350_final_project
```

### 2. Set Up the Environment

Install required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn statsmodels quarto
```

You may also need to install **Quarto CLI** if you want to render the `.qmd` report:
- [Install Quarto](https://quarto.org/docs/get-started/)

### 3. Run the Scripts

- Data analysis:  
  ```bash
  python scripts/data_analysis.py
  ```
- Regression modeling:  
  ```bash
  python scripts/regression_models.py
  ```

### 4. View the Final Report

Open the `report/report.html` file in your browser to explore the full findings, graphs, and interpretations.

---

## 📊 Technologies Used

| Tool | Purpose |
|:-----|:--------|
| **Python 3.10+** | Main programming language |
| **Pandas** | Data manipulation |
| **NumPy** | Numerical operations |
| **Matplotlib & Seaborn** | Data visualization |
| **Statsmodels** | Regression modeling |
| **Quarto** | Report generation (HTML/Markdown) |

---

## 👥 Team Members

- Jacky An  
- Bernice  
- Eric  

Each team member contributed to different parts of the project, including data cleaning, exploratory analysis, statistical modeling, and report writing.

---

## 🙏 Acknowledgments

- **World Bank Group**: For providing open access to the WDI database.
- **Professor Danilo Freire**: For his guidance and feedback throughout the project.

---

## 📄 License

This project is for academic use only under the guidelines of QTM350 coursework.  
No commercial use permitted without permission.

---

## 🚀 Quick Links

- [Quarto Documentation](https://quarto.org/docs/)
- [World Bank WDI Dataset](https://databank.worldbank.org/source/world-development-indicators)
