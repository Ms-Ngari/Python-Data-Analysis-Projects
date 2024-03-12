# Water Quality Analysis

# 📌 Overview
Access to safe drinking water is a fundamental human right and a critical public health issue. This project analyzes water quality data using Python, focusing on key water potability indicators such as pH, hardness, dissolved solids, chloramines, sulfate levels, and turbidity. The goal is to assess water quality and determine its suitability for human consumption.

# 🛠 Technologies Used
- Python
- Pandas, NumPy – Data handling and manipulation
- Matplotlib, Seaborn – Data visualization
- Scikit-learn – Machine learning models (if applicable)

# 📂 Dataset
The dataset (water_potability.csv) contains 3,276 water samples with various quality metrics:

| Feature                         | Description |
|---------------------------------|-------------|
| **pH**                          | Measures the acidity/alkalinity of water (WHO recommended: 6.5 – 8.5) |
| **Hardness**                    | Indicates calcium and magnesium salt content |
| **Total Dissolved Solids (TDS)** | Reflects mineralization level (Desirable: <500 mg/L, Max: 1000 mg/L) |
| **Chloramines**                  | Disinfectants used in water treatment (Safe: ≤4 mg/L) |
| **Sulfate**                      | Naturally occurring in water (Safe: 3 – 30 mg/L, but can be higher in some regions) |
| **Conductivity**                 | Measures the water’s ability to conduct electricity (WHO limit: ≤400 µS/cm) |
| **Organic Carbon**               | Presence of decaying organic material (Safe: <4 mg/L) |
| **Trihalomethanes (THMs)**       | Byproduct of chlorination (Safe: ≤80 ppm) |
| **Turbidity**                    | Cloudiness of water (WHO limit: ≤5 NTU) |
| **Potability**                   | Indicates whether water is safe for drinking (1 = Potable, 0 = Not Potable) |

## 🔍 Key Analyses
- Data Cleaning & Preprocessing – Handling missing values, outliers, and data type conversions
- Exploratory Data Analysis (EDA) – Understanding water quality trends and distributions
- Correlation Analysis – Identifying relationships between features and potability
- Data Visualization – Graphical representation of safe vs. unsafe water samples

## 📊 Insights
- Identifying which parameters most influence water potability
- Determining the proportion of potable vs. non-potable water sources
- Visualizing how water quality varies across different parameters

## 🚀 How to Run the Analysis
- Clone this repository
- Install dependencies:
```python
install pandas numpy matplotlib seaborn scikit-learn
```
- Load and explore the dataset in a Jupyter Notebook
- Run the analysis and visualize the results

## 📢 Conclusion
This project provides valuable insights into water quality assessment, helping identify key factors affecting potability. The analysis can support water safety monitoring, policy-making, and public health initiatives.
Contributions and suggestions are welcome! 🌍💙
