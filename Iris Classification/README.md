
# Iris Flower Classification

## Overview

This project uses machine learning to classify iris flowers into three species—**Setosa**, **Versicolor**, and **Virginica**—based on their sepal and petal measurements. The Iris dataset is a classic dataset in pattern recognition and is often used for learning and testing machine learning algorithms.

---

## Dataset

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris) or [Scikit-learn built-in dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)
- **Features:**
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)
- **Target:**
  - Species: Setosa, Versicolor, Virginica

---

## Project Structure

```python
Iris_Classification
│
├── iris_classification.ipynb   # Jupyter notebook with code and analysis
├── iris.csv                    # Dataset (if not using sklearn's built-in)
├── README.md                   # Project documentation
└── requirements.txt            # List of dependencies
```

---

## How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Yashsmakwana/OIBSIP.git
   cd Iris_Classification
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook:**
   - Open `iris classification.ipynb` in Jupyter Notebook or JupyterLab.
   - Run the cells step by step.

---

## Steps Performed

1. **Data Loading:**  
   Load the Iris dataset using pandas or scikit-learn.

2. **Data Exploration:**  
   View the first few rows, check for missing values, and understand the data structure.

3. **Data Visualization:**  
   Use seaborn and matplotlib to visualize feature distributions and relationships.

4. **Data Preprocessing:**  
   Split the data into training and test sets.

5. **Model Training:**  
   Train a K-Nearest Neighbors (KNN) classifier (and optionally other models).

6. **Model Evaluation:**  
   Evaluate the model using accuracy and confusion matrix.

7. **Prediction:**  
   Predict the species of new iris flowers based on their measurements.

---

## Results

- **Accuracy:** Achieved over 95% accuracy on the test set.
- **Best Model:** KNN classifier performed well; other models like Decision Tree and Random Forest can also be tried.

---

## Example Usage

```python
# Predict species for a new flower
new_flower = [[5.1, 3.5, 1.4, 0.2]]
prediction = model.predict(new_flower)
print("Predicted species:", prediction[0])
```

---

## Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

- [Scikit-learn documentation](https://scikit-learn.org/)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
