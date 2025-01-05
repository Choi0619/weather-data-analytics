# 🌟 Weather Data Analytics with PySpark

This project focuses on analyzing weather data using PySpark for large-scale data processing and analytics. The analysis includes integrating data from multiple sources, transforming it, and extracting insights such as temperature trends and statistical summaries.

---

## 🛠 Project Highlights

- **Data Integration**:
  - Loaded weather data from **MinIO** (S3-compatible object storage).
  - Retrieved additional data from a **MySQL** database.

- **Data Analytics**:
  - Combined datasets to create a unified view for analysis.
  - Filtered February data and removed outliers to ensure data quality.
  - Performed statistical analyses, including:
    1. Total record count.
    2. Average air temperature.
    3. Median air temperature.
    4. Standard deviation of air temperature.
    5. Average temperature per weather station.

- **Output**:
  - Saved results as single-partition CSV files for easy access.

---

## 📊 Key Results

- **Temperature Trends**:
  - Identified yearly changes in air temperature for February.
  - Analyzed temperature variation across weather stations.

- **Statistical Insights**:
  - Provided aggregate metrics like averages, medians, and standard deviations.

---

## 🚀 Repository Structure

- `weather_data_analysis.ipynb`: The primary notebook containing all code and analysis.
- `README.md`: Overview of the project.
- CSV outputs: Results of queries saved in the project directory.

---

## 💻 Requirements

- Python 3.x
- Libraries: `pyspark`, `pandas`, `numpy`
- Access to MinIO and MySQL.

---

## 📝 Future Work

- Expand the analysis to other months or seasons.
- Incorporate additional weather metrics for deeper insights.
- Experiment with visualization libraries to present findings interactively.

---

**Explore the project to learn more about PySpark for data integration and analytics! 😊**
