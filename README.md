# COVID-19 Global Data Analysis Project

## 📋 Project Description
This project analyzes global COVID-19 data using **Google BigQuery**, **SQL**, and **Python** (Pandas, Matplotlib, Plotly, Scikit-Learn).  
The goal is to detect pandemic patterns, identify anomaly spikes, cluster countries based on severity, and create insightful visualizations.

---

## 🛠 Technologies Used
- **Google BigQuery** (SQL queries on public datasets)
- **Pandas** for data cleaning and transformation
- **Matplotlib** and **Plotly** for visualization
- **Scikit-Learn** (KMeans clustering)
- **Anomaly Detection** using Z-Score method

---

## 📈 Key Analyses Performed
- Extracted and aggregated COVID-19 case data globally
- Detected **daily case anomalies** using statistical Z-scores
- Created **interactive world map** showing total case distribution
- Applied **KMeans clustering** to group countries based on cases and deaths
- Visualized **daily trends** and **7-day rolling averages** for the USA

---

## 📊 Results
- Identified countries with highest outbreaks
- Detected major anomaly surges (e.g., USA waves)
- Clustered countries into distinct risk groups based on COVID impact
- Provided clean visual storytelling through charts and maps

---

## 📚 Dataset
- Public dataset: [`bigquery-public-data.covid19_open_data.covid19_open_data`]([https://console.cloud.google.com/marketplace/product/bigquery-public-data/covid19-open-data])

---

## 🧠 Insights
- COVID cases showed major spikes corresponding to known pandemic waves.
- Certain countries experienced steeper death-to-case ratios.
- Clustering revealed high-impact vs low-impact country groups, useful for global response strategies.

---

## 🚀 Future Improvements
- Forecast case trends using time-series models
- Deeper clustering with more features (e.g., vaccination rates)
- Build a Streamlit dashboard for interactive visualization

---
