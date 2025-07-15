# Unemployment Rate Analysis in India

## Overview

This project analyzes the unemployment rate in India using data science techniques. The goal is to explore, visualize, and understand unemployment trends over time and across different regions, especially during significant events like the Covid-19 pandemic.

---

## Dataset

- **Source:** [Kaggle - Unemployment in India](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)
---
- **Features:**
  - Date/Month
  - Region/State
  - Estimated Unemployment Rate (%)
  - Estimated Employed
  - Estimated Labour Participation Rate (%)
  - Area (Urban/Rural)
---
- **Target:**
  - Unemployment Rate (%)

---

## Project Structure:
```python
Unemployment Analysis/ 
│ 
├── Unemployment in india.ipynb # Jupyter notebook with code and analysis 
├── Unemployment in India.csv   # Dataset (or link to Kaggle) 
├── README.md                   # Project documentation 
├── requirements.txt            # List of dependencies 
└── plots/                      # (Optional) Folder for images/plots

```
---

## How to Run:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Yashsmakwana/OIBSIP.git
   cd Unemployment_Analysis

### Install dependencies:
  ```bash
  pip install -r requirements.txt 
  ```

### Run the notebook:
Open Unemployment in india.ipynb in Jupyter Notebook or JupyterLab.
Run the cells step by step.

### Steps Performed:

Data Loading:
Load the unemployment dataset using pandas.

Data Exploration:
View the first few rows, check for missing values, and understand the data structure.

Data Visualization:
Use seaborn and matplotlib to visualize unemployment trends over time and by region.

Data Preprocessing:
Clean column names, handle missing values, and convert date columns.
---

### Analysis:

Visualize unemployment rate over time.
Compare unemployment rates across regions.
Identify periods of high and low unemployment.

#### (Optional) Modeling:
Predict future unemployment rates using regression models.

Results:
Visualized unemployment trends over time and by region.
Identified regions and periods with the highest and lowest unemployment rates.
(Optional) Built a simple model to forecast unemployment.
---
#### Example Visualization:
```python
plt.figure(figsize=(12,6))
sns.lineplot(x='Date', y='Estimated Unemployment Rate (%)', data=df)
plt.title('Unemployment Rate in India Over Time')
plt.xlabel('Date')
plt.ylabel('Unemployment Rate (%)')
plt.show()
```
#### Dependencies:
Python 3.x
pandas
numpy
matplotlib
seaborn
kagglehub (if loading from Kaggle)
scikit-learn (if using machine learning)

#### License:
This project is licensed under the MIT License.

#### Acknowledgements:
Kaggle - Unemployment in India Dataset
pandas documentation
seaborn documentation

---
