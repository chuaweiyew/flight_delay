# flight_delay
Find trends between flights and flight delays
# ✈️ Flight Delay Analysis and Prediction

## 📌 Introduction

Flight delays are a costly and persistent issue in the aviation industry, impacting airlines, airports, and passengers. According to the Federal Aviation Administration (FAA), a flight is considered **delayed** when it departs or arrives more than **15 minutes** later than scheduled.

This project explores delay patterns and attempts to build predictive models using historical flight data. Through this research, we aim to identify trends, causes, and potential mitigations for flight delays.

---

## 🎯 Research Questions

1. **When is the best time to fly (time of day, day of the week, or season) to minimize delays?**
2. **Do older aircraft experience more delays than newer ones?**
3. **How does passenger traffic between different locations evolve over time?**
4. **Can we detect cascading failures—when delays in one airport trigger delays in others?**
5. **Can we build a predictive model using available variables to estimate the likelihood of a delay?**

---

## 📊 Data Sources

The data used in this project was sourced from the [Harvard Dataverse](https://doi.org/10.7910/DVN/HG7NV7), and includes:

- **Flight data for 2004 & 2005**
- **Carrier information**
- **Airport metadata**
- **Aircraft/plane details**

---

## 🧰 Tools & Languages Used

- **SQL** – Merging and preprocessing data from multiple tables
- **Python** – Data cleaning, exploratory data analysis (EDA), visualizations, and model building (e.g., using pandas, matplotlib, scikit-learn)
- **R** – Statistical analysis and advanced visualizations (e.g., using ggplot2, dplyr)

---

## 🗂️ Files Included

- `data/` - folder containing all data files used
  - `airline2_r.db` - database created
  - `2004.csv` - flight data for 2004
  - `2005.csv` - flight data for 2005
  - `airports.csv` - airport data
  - `carriers.csv` - carrier data
  - `plane-data.csv` -plane data
- `notebooks/` - folder containing python notebook files
  - `question_1_2_3_4(notebook).ipynb` - python notebook for questions 1,2,3,4
  - `question_5(notebook).ipynb` - python notebook for questions 5
- `R Markdown/` - folder containing R Markdown files
  - `question_1_2_3_4(R_markdown).Rmd` - R markdown file for questions 1,2,3,4
  - `question_5(R_markdown).Rmd` - R markdown file for questions 5
- `summary_report.pdf` – PDF write-up including key visuals and insights
- `README.md` – this file

---

## 📈 Highlights

- Identified **low-risk travel periods** based on temporal patterns
- Discovered a correlation between **aircraft age and delay likelihood**
- Modeled passenger movement trends using time-series analysis
- Detected **network delay effects** between major U.S. airports
- Built a **predictive model** using logistic regression and decision trees to estimate delay probability

---

## 📬 Contact

Connect with me on [LinkedIn](https://www.linkedin.com/in/wei-yew-c-a809b828a/).
