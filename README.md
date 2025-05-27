# Iristask2
# 🌸 Iris Dataset - Exploratory Data Analysis (EDA)

This project performs comprehensive **Exploratory Data Analysis** on the classic **Iris dataset** using Python. It includes summary statistics, visualizations, data cleaning, and feature-level insights.

---

## 🎯 Objective

Understand the Iris dataset using **statistics** and **visualizations** to:

- Summarize data distributions
- Detect and handle outliers
- Visualize relationships between features
- Save a cleaned dataset for future use

---

## 🛠️ Tools & Libraries

- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib / Seaborn** – data visualization
- **Scikit-learn** – dataset loading, preprocessing
- **Plotly** (optional) – interactive visualizations

---

## 📦 Dataset

- **Name:** Iris Flower Dataset
- **Source:** scikit-learn (`sklearn.datasets.load_iris()`)

Contains 150 samples across 3 classes:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

Each with 4 features:
- Sepal length
- Sepal width
- Petal length
- Petal width

---

## 📈 EDA Workflow

1. **Load the dataset**
2. **Display structure** and check for missing values
3. **Generate summary statistics**
4. **Encode species labels**
5. **Scale numeric features** using `StandardScaler`
6. **Visualize distributions** using histograms and boxplots
7. **Detect & remove outliers** using the IQR method
8. **Save the cleaned dataset** (`iris_cleaned.csv`)

---

## 📂 Output

- Cleaned dataset: `iris_cleaned.csv`
- Visualizations: Inline plots (histograms, boxplots)
- Optional interactive plots (if using Plotly)

---

## ▶️ How to Run

1. Clone this repository or copy the notebook code.
2. Install dependencies (see below).
3. Run the notebook in **VS Code**, **Jupyter Notebook**, or **Google Colab**.

---

## 🧪 Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
# Optional for interactive plots:
pip install plotly

Example Visuals

Histograms of scaled features
Boxplots for outlier detection
Correlation heatmaps
Pairplots or scatter matrices
📌 Notes

Features are scaled to improve visual clarity.
Outliers are removed using IQR method.
Encoded target values are included for modeling.
📚 References

Scikit-learn Iris Dataset
Seaborn Documentation
Plotly for Python

opensource and free to use
