# 🌸 Iris Flower Classification

A machine learning project that classifies Iris flowers into three species — **Setosa**, **Versicolor**, and **Virginica** — based on their sepal and petal measurements. Built as part of the **CodeAlpha Data Science Internship**.

---

## 📌 Project Overview

The Iris dataset is one of the most well-known datasets in machine learning. This project walks through the full data science pipeline:

- Loading and exploring the dataset
- Visualizing feature distributions and correlations
- Training and comparing multiple classification models
- Evaluating performance with accuracy scores and confusion matrices
- Predicting the species of a new unseen flower

---

## 🗂️ Project Structure

```
CodeAlpha_IrisFlowerClassification/
│
├── iris_classification.ipynb     # Main Kaggle notebook
├── iris_exploration.png          # Visualization charts (EDA)
├── iris_results.png              # Model comparison & confusion matrix
└── README.md                     # Project documentation
```

---
## Source
| Source | [Kaggle](https://www.kaggle.com/code/yacinebouachrine/iris-flower-classification) 
---

## 📊 Dataset

| Feature | Description |
|---|---|
| `sepal length (cm)` | Length of the sepal |
| `sepal width (cm)` | Width of the sepal |
| `petal length (cm)` | Length of the petal |
| `petal width (cm)` | Width of the petal |
| `species` | Target class: Setosa (0), Versicolor (1), Virginica (2) |

- **150 samples** — 50 per species
- **4 features**, 1 target variable
- **No missing values**
- Source: Built-in `sklearn.datasets.load_iris()`

---

## ⚙️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Model training & evaluation |

---

## 🔄 Pipeline

```
Load Data → Explore & Visualize → Preprocess → Train Models → Evaluate → Predict
```

### Steps in detail

1. **Load Data** — Import the Iris dataset from Scikit-learn and build a DataFrame
2. **Explore** — Check shape, class distribution, statistics, and missing values
3. **Visualize** — Bar charts, scatter plots, histograms, and correlation heatmap
4. **Preprocess** — Train/test split (80/20) + StandardScaler normalization
5. **Train** — Fit 3 classification models
6. **Evaluate** — Compare accuracy, classification report, and confusion matrix
7. **Predict** — Test the best model on a new custom flower sample

---

## 🤖 Models Used

| Model | Description |
|---|---|
| K-Nearest Neighbors (KNN) | Classifies based on the K closest training points |
| Decision Tree | Splits data using feature thresholds |
| Random Forest | Ensemble of 100 decision trees |

---

## 📈 Results

> Results may vary slightly depending on the random state.

| Model | Accuracy |
|---|---|
| K-Nearest Neighbors | ~96.67% |
| Decision Tree | ~96.67% |
| **Random Forest** | **~96.67%** |

All three models perform excellently on this dataset. The confusion matrix confirms that **Setosa** is perfectly classified, while minor confusion may occur between **Versicolor** and **Virginica** due to overlapping features.

---

## 🚀 How to Run

### On Kaggle
1. Open a new Kaggle Notebook
2. Paste each cell from `iris_classification.ipynb` in order
3. Click **Run All**
4. No dataset download needed — the Iris dataset is built into Scikit-learn

### Locally
```bash
# Clone the repository
git clone https://github.com/your-username/CodeAlpha_IrisFlowerClassification.git
cd CodeAlpha_IrisFlowerClassification

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# Run the notebook
jupyter notebook iris_classification.ipynb
```

---

## 🔮 Sample Prediction

```python
new_flower = np.array([[5.1, 3.5, 1.4, 0.2]])
# → Predicted species: Setosa
```

You can change these 4 values (sepal length, sepal width, petal length, petal width) to classify any custom flower.

---

## 📚 Key Learnings

- How to perform exploratory data analysis (EDA) on a classification dataset
- How to preprocess data using train/test split and feature scaling
- How to train and compare multiple ML models using Scikit-learn
- How to interpret a confusion matrix and classification report
- How to make predictions on new unseen data

---

## 🏢 About

This project was completed as **Task 1** of the **CodeAlpha Data Science Internship**.

- 🌐 Website: [www.codealpha.tech](https://www.codealpha.tech)
- 📧 Email: services@codealpha.tech

---

## 👤 Author

**Your Name**
- GitHub: [yassinebouachrine](https://github.com/yassinebouachrine)
- LinkedIn: [yassinebouachrine](https://linkedin.com/in/yassine-bouachrine-68b761230)

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
>>>>>>> 2b824a8f6b02336f98e72b3e0639e1e736688b50
