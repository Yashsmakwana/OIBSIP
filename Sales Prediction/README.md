# Sales Prediction with Machine Learning

## Overview

This project demonstrates how to use machine learning to predict product sales based on advertising spend across different media channels (TV, Radio, Newspaper). The project uses the classic Advertising dataset and walks through data exploration, visualization, model training, evaluation, and prediction.

---

## Dataset

- **Source:** [Kaggle - Advertising.csv](https://www.kaggle.com/datasets/bumba5341/advertisingcsv) or [StatLearning Advertising Data](https://www.statlearning.com/s/Advertising.csv)
- **Features:**
  - TV advertising spend
  - Radio advertising spend
  - Newspaper advertising spend
- **Target:**
  - Sales

---

## Project Structure

```python
sales-prediction/
│
├── Sales Prediction.ipynb    # Jupyter notebook with code and analysis
├── Advertising.csv           # Dataset (or link to Kaggle)
├── README.md                 # Project documentation
├── requirements.txt          # List of dependencies
└── plots/                    # (Optional) Folder for images/plots
```

---

## How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/sales-prediction.git
   cd sales-prediction
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook:**
   - Open `Sales Prediction.ipynb` in Jupyter Notebook or JupyterLab.
   - Run the cells step by step.

---

## Steps Performed

1. **Data Loading:**  
   Load the advertising dataset using pandas.

2. **Data Exploration:**  
   View the first few rows, check for missing values, and understand the data structure.

3. **Data Visualization:**  
   Use seaborn and matplotlib to visualize relationships between ad spend and sales.

4. **Data Preprocessing:**  
   Select features, split data into training and test sets.

5. **Model Training:**  
   Train regression models (Linear Regression, Random Forest, etc.).

6. **Model Evaluation:**  
   Evaluate models using RMSE and R² score.

7. **Prediction:**  
   Predict sales for new advertising campaigns.

---

## Results

- Built regression models to predict sales based on advertising spend.
- Achieved high accuracy with Random Forest Regression (R² > 0.95).
- TV and Radio ad spend were found to be the most important features.

---

## Example Usage

```python
# Predict sales for a new campaign
new_data = [[200, 50, 30]]  # TV, Radio, Newspaper
predicted_sales = model.predict(new_data)
print(f"Predicted Sales: {predicted_sales[0]:.2f}")
```

---

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- kagglehub (if loading from Kaggle)

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

- [Kaggle - Advertising.csv Dataset](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)
- [StatLearning Advertising Data](https://www.statlearning.com/s/Advertising.csv)
- [pandas documentation](https://pandas.pydata.org/)
- [scikit-learn documentation](https://scikit-learn.org/)
```

---
