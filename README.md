

---

# 🌍 COVID-19 Data Analysis & Visualization Project

## 📘 Overview

This project presents a data-driven analysis of global COVID-19 trends using a dataset from [Our World in Data](https://ourworldindata.org/coronavirus). The goal is to explore the pandemic’s impact across different countries by analyzing cases, deaths, and vaccination statistics through visual storytelling using Python and Jupyter Notebook.

## 🎯 Project Objectives

- Load and explore COVID-19 data using `pandas`
- Clean and preprocess the dataset to handle missing values
- Perform exploratory data analysis (EDA) on cases, deaths, and vaccinations
- Create compelling visualizations to communicate trends and key insights
- Calculate and analyze key indicators such as:
  - Daily new cases
  - Death rates over time
  - Vaccination coverage

## 📊 Dataset

- **Source:** [Our World in Data - COVID-19 Dataset](https://github.com/owid/covid-19-data)
- **Format:** CSV
- **Size:** ~429,000 rows, 67 columns
- **Columns used:**
  - `location`, `date`, `total_cases`, `new_cases`, `total_deaths`, `people_vaccinated`, `people_fully_vaccinated`, etc.

## 🔧 Tools & Libraries

- Python
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- numpy

## 📈 Visualizations Included

- Line chart: Daily new COVID-19 cases (Kenya, US, India, Brazil, South Africa)
- Line chart: Death rates over time by country
- Line chart: Vaccination coverage over time
- Bar charts and trend plots to support key insights

## ✅ Key Insights

- Identified significant peaks and waves in daily case numbers
- Compared country-level death rates over time
- Analyzed vaccination uptake and impact across selected countries
- Explored how the pandemic evolved over time globally and regionally

## 📁 Project Structure

```

covid\_data\_analysis/
│
├── data/
│   └── owid-covid-data.csv         # Main dataset
│
├── covid\_analysis.ipynb           # Final Jupyter Notebook report
├── README.md                      # Project overview and instructions
└── requirements.txt               # Dependencies (optional)

````

## 💡 How to Run

1. Clone the repository or download the project files.
2. Open the notebook with Jupyter:
   ```bash
   jupyter notebook covid_analysis.ipynb
````

3. Ensure `owid-covid-data.csv` is placed inside the `data/` directory.
4. Run all cells to see the full analysis and visualizations.

## ✨ Optional Stretch Goals (Not Implemented)

* [ ] Add interactive features (e.g., user input for country/date range)
* [ ] Build a Streamlit dashboard
* [ ] Include hospitalization or ICU data in more depth

## 📜 Final Deliverable

* ✅ A self-contained, well-documented Jupyter Notebook that:

  * Loads, cleans, and analyzes the data
  * Visualizes trends with clear labeling
  * Is readable and reproducible for anyone with basic Python knowledge

## 🙌 Acknowledgements

* Data Source: [Our World in Data](https://ourworldindata.org/coronavirus)
* Python open-source ecosystem: pandas, matplotlib, seaborn, Jupyter

---

```

---

