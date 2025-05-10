# 🦠 COVID-19 Global Data Tracker

This project presents a detailed analysis and visualization of global COVID-19 trends, including cases, deaths, and vaccinations. Built using Python in Jupyter Notebook (via VS Code), it leverages real-world data from **Our World in Data**.

---

##  Project Objectives

-  Import and clean global COVID-19 data
-  Analyze time-series trends for cases, deaths, and vaccinations
-  Compare countries (Kenya, USA, India)
-  Visualize insights using line charts, bar charts, pie charts, and choropleth maps
-  Deliver a publishable notebook/report with insights and visuals

##  Key Technologies Used

- **Python (pandas, matplotlib, seaborn, plotly)**
- **Jupyter Notebook** (in VS Code)
- **Plotly Express** for interactive world maps
- **Data Source**: [Our World in Data](https://github.com/owid/covid-19-data)

---

##  Data Overview

-  Time series data by country
-  Key fields: `date`, `location`, `total_cases`, `total_deaths`, `new_cases`, `total_vaccinations`, `people_fully_vaccinated`, `population`
-  Focus Countries: **Kenya**, **United States**, **India**

---

##  Main Visualizations

- Line plots for:
  - Total cases and deaths over time
  - Daily new cases
  - Vaccination rollouts
  - % Fully vaccinated population
- Pie charts comparing vaccinated vs. unvaccinated
- Choropleth maps (Plotly) for:
  - Total cases by country
  - Vaccination rates by country

---

##  Key Insights

1. The U.S. had the highest number of cumulative cases and deaths.
2. India experienced severe waves, especially during early 2021.
3. Kenya's outbreaks were smaller but occurred in regular cycles.
4. All countries showed increasing vaccine coverage, with the U.S. leading early.
5. Choropleth maps highlight disparities in vaccination across regions.

---

## 📤 How to Run

> Requirements:
- Python 3.8+
- Jupyter or VS Code with Jupyter extension

```bash
# Install dependencies
pip install pandas matplotlib seaborn plotly jupyter

# Launch notebook
jupyter notebook

