# 📘 air-conditioner-regression-analysis



This notebook contains exploratory data analysis, model training, and evaluation on an air conditioner prices dataset

---

## 📂 Contents

1. **Data Summary**
   - Dataset shape and sample inspection using `.head()`, `.info()`, `.describe()`
   - Identification of continuous and categorical attributes

2. **Visualizations and Statistics**
   - Histograms for continuous features
   - Boxplots to explore distributions and detect outliers
   - Correlation heatmap

3. **Linear Regression and Regularization (Part E)**
   - Linear Regression with closed-form solution (Normal Equation/SVD)
   - Linear Regression with Stochastic Gradient Descent (SGD)
   - Regularization using Ridge, Lasso, and Elastic Net
   - Impact analysis of different penalty terms
   - Exploration of hyperparameters like batch size and learning rate
   - Training and validation loss plotted across iterations for SGD

4. **Polynomial Regression with SGD (Part F)**
   - Polynomial feature expansion
   - Model training using SGD
   - Validation loss analysis for detecting overfitting/underfitting
   - Impact of hyperparameters and degree of polynomial features

5. **Insights and Observations**
   - Key takeaways from visual trends, modeling behavior, and hyperparameter tuning

---

## 📊 Dataset

The dataset consists of air conditioner listings with various features such as:
- Brand
- Model
- Star rating
- Cooling capacity
- Price, etc.

(*Exact attributes are visible in the early notebook cells*)

---

## 🛠️ Requirements

To run this notebook, you'll need:

```bash
Python 3.x
pandas
numpy
matplotlib
seaborn
scikit-learn
```

Install dependencies via:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🚀 Usage

Clone the repository or download the notebook, then open it with Jupyter:

```bash
jupyter notebook AML-Assignment1PartB.ipynb
```

---

## 📎 Notes

This analysis focuses on:
- Understanding data structure
- Visualization-driven insights
- Linear and Polynomial Regression modeling
- Hyperparameter impact analysis
- Regularization techniques (Ridge, Lasso, Elastic Net)
