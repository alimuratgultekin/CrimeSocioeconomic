# 📌 Phase 1: Project Proposal

# 📊 Analysis of Crime Rate and Socioeconomic Factors. 

## 📝  Project Proposal Outline
This project is an investigation of the **relationships between crime rates and socio-economic  factors** like **income**, **education**, and **employment rates** across different regions. The study aims  to identify **patterns, correlations, and predictive factors** of crime rates by analyzing publicly available crime and  economic datasets. The purpose is to offer **data-driven findings** that can assist policymakers and law enforcement  agencies in the **design of efficient crime fighting policies**.

---

## 📝 Motivation
 The importance of understanding the relationship between **socioeconomic status and crime** is essential in the formulation  of policies that can reduce crime rates. Previous studies have shown that crime may be associated with  **poverty, unemployment, low levels of education, and economic inequality**. To these ends, this project  will try to answer the following key questions:  
- **Are areas with low income more likely to  experience high crime rates?**  
- **Does higher education lead to reduced crime?**  
-  **Which of the socio-economic factors are most likely to be associated with crime?**  

Through  **Exploratory Data Analysis (EDA), hypothesis testing, and correlation studies**, this project will give  **quantifiable results** on the effects of social and economic conditions on crime.

---

## 📂  Dataset
The dataset will consist of **crime statistics** and **socioeconomic indicators** to look  at possible links between the two.

### 1️⃣ Crime Data Sources
-  **FBI Uniform Crime Reporting (UCR) Database** – Contains detailed crime statistics across US states and  cities.
- **Kaggle Open Crime Datasets** – Different publicly available crime datasets from all  over the world organized by type, level and region.

### 2️⃣  Socioeconomic Data Sources
- **World Bank Reports** – Includes information on **income, employment and  education** across various countries.  
- **US Census Bureau / European Commission Economic Reports** – Has  **demographic and economic characteristics** that can be linked to crime data.

###  3️⃣ Additional Data (Enhancements)
- **Neighborhood Safety Index Data** – To determine the general  **perception of safety** in various areas.
- **Housing Price Data** – Property values  may be related to the wealth of the neighborhood and can be related to crime rates.

---

##  📌 Data Collection and Preprocessing Plan
For a more meaningful analysis, data from **many  sources** will be gathered and combined based on geographic location (city, state, or postal code).

###  **1️⃣ Data Collection**
- Download **historical crime data** for several cities  and states.
- Collect **socioeconomic characteristics** for the same areas.

###  **2️⃣ Data Preprocessing**
- **Clean and standardize** the dataset formats.
- Manage  **missing values and incomplete or inconsistent records**.
- Combine **crime and socioeconomic data** by a  common field, for instance, city or state.

### **3️⃣ Exploratory  Data Analysis (EDA)**
- Present **descriptive statistics** of the data.
- Make  **visualizations** (heatmaps, scatter plots, histograms) to look for relationships.
- Look for  any **outliers or biases** in the dataset.

---

## 📊 Data Analysis Plan
 This project will be conducted in the following stages:

### 🔹 Exploratory Data Analysis (EDA)
 - **Crime Trends:** Presentation of how crime rates vary with time and across different socioeconomic categories.  
 - **Correlation Analysis:** Determine the relationships between crime and **income, education, and  unemployment**.
- **Geospatial Mapping:** Use **heatmaps** to show where crimes occur and  how they relate to the economy.

### 🔹 Hypothesis Testing
#### **Hypothesis  1:**  
📌 **H₀ (Null Hypothesis):** There is no  statistical relationship between socio-economic factors (income, education, employment) and crime rates.  
 📌 **H₁ (Alternative Hypothesis):** One or more socio-economic factors are the  determinants of crime rates.

### 🔹 Comparative Analysis
- Compares **high crime areas** and  **low crime areas** to compare the level of income, education and other characteristics.  
- To  check if **rich areas** have lower crime rates than **poor areas**.

### 🔹  Trend and Predictive Modeling (Future Steps)
- Determine whether there is a link between  **improving the economy and decreasing crime** over time.
- May apply **machine learning techniques** to forecast  crime rates based on socio-economic variables.

---

## 🏛  Expected Findings
This project is expected to reveal some **important characteristics** regarding how socio-economic factors  **affected crime rates**, such as:  
✅ **Low education may be connected with higher crime  rates.**  
✅ **Some unemployment situations may be related to specific crimes.**  
✅ **Some economic factors (for instance, income inequality) may be better predictors of crime than  others.**  

Findings will be **presented in charts and maps** for easier understanding.

---

 ## 🔍 Limitations and Future Work
### 📉 Limitations
- **Incomplete or  biased datasets** (some crimes can go unreported).
- **Correlation does not mean  Causation** (though crime and income may be related, there may be other factors at work).
-  **Regional differences** (different cities have different laws and police policies).

### 🚀 Future Work
 - Extend the analysis to **regional, national, and international crime rates**.
- Apply  **machine learning models** to forecast crime rates.
- Incorporate **real-time data sources**  (for instance, real-time crime reports).

---

## 📜 Ethical Considerations
-  **Privacy:** All datasets used shall be **available and anonymous**.
- **Bias Awareness:** The analysis  will take into consideration possible prejudice in crime reporting.
- **Transparency:** All data sources and methodologies  will be fully documented.


# 📊 Phase 2: Data Collection, EDA, and Hypothesis Testing

# 📊 Analysis of Crime Rates and Socioeconomic Factors

## 🚀 Project Overview
This project investigates the relationship between crime rates and socioeconomic factors such as education levels and unemployment rates across various U.S. cities and states. The goal is to identify potential correlations that could inform policies aimed at reducing crime.

---

## 📂 Data Collection
- **Crime Data Source:**  
  FBI Crime Data Explorer (2023) — City-level crime statistics for violent and property crimes.
  
- **Socioeconomic Data Sources:**  
  USDA Economic Research Service (2023) — State-level data on:
  - % of adults with a bachelor's degree or higher.
  - Unemployment rates.

- The datasets were cleaned and merged based on state and city information.  
  Final datasets are available in the `/data` folder.

---

## 📊 Exploratory Data Analysis (EDA)
- Descriptive statistics revealed:
  - Average education level: ~26.6% with a bachelor's degree.
  - Average unemployment rate: ~3.8%.
  - High variability in crime counts due to population differences.

- **Correlation Heatmap** indicated:
  - Very weak negative correlation between education and crime rates.
  - Slight positive correlation between unemployment and property crime.

- **Visualizations:**
  - ![Correlation Heatmap](exploratory%20data%20analysis/correlation_heatmap.png)
  - ![Violent Crime vs Education](exploratory%20data%20analysis/scatter_violent_vs_education.png)
  - ![Property Crime vs Unemployment](exploratory%20data%20analysis/scatter_property_vs_unemployment.png)

More details and plots can be found in the `/exploratory data analysis` folder.

---

## 🧪 Hypothesis Testing
Two hypotheses were tested:

1️⃣ **Education vs. Violent Crime**  
- **H₀:** No correlation between education level and violent crime.  
- **Result:**  
   - Pearson r = 0.0041 (p = 0.706) ➜ No significant linear correlation.  
   - Spearman ρ = 0.0406 (p < 0.001) ➜ Statistically significant but negligible.

2️⃣ **Unemployment vs. Property Crime**  
- **H₀:** No correlation between unemployment rate and property crime.  
- **Result:**  
   - Pearson r = 0.0537 (p < 0.001) ➜ Weak but significant linear correlation.  
   - Spearman ρ = 0.1453 (p < 0.001) ➜ Weak positive monotonic correlation.

📄 Full results are available in the `/hypothesis-testing/hypothesis_testing_results.csv`.

---

## 🎯 Findings & Insights
- No meaningful relationship was found between education levels and violent crime rates.
- A weak but statistically significant relationship exists between unemployment rates and property crime.
- These results suggest that while socioeconomic factors may influence crime, they are not sole predictors.

---

## ⚠️ Limitations
- Crime data used raw counts instead of per capita rates.
- Socioeconomic data was aggregated at the state level, which may overlook local variations.
- Only 2023 data was analyzed; trends over time were not considered.

---

## 🚀 Next Steps
- In future phases, apply machine learning models to explore predictive capabilities.
- Incorporate additional factors such as income levels, poverty rates, and urbanization.

---
