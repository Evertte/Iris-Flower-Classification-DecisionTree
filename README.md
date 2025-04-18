# 🌸 Iris Flower Classification using Decision Tree

This project applies a **Decision Tree Classifier** to predict the species of iris flowers using the well-known `iris.csv` dataset. The goal is to classify flowers into one of three species based on their physical features.

---

## 📚 Dataset Overview

The dataset contains 150 samples with the following features:

- `sepal length (cm)`
- `sepal width (cm)`
- `petal length (cm)`
- `petal width (cm)`
- `species` (Target variable: Setosa, Versicolor, Virginica)

---

## 🧰 Tools & Libraries Used

- **Python** 🐍
- **pandas** – For data manipulation and loading
- **matplotlib** & **seaborn** – For data visualization and plotting
- **scikit-learn** – For machine learning algorithms and model evaluation
  - `DecisionTreeClassifier` – Classification model
  - `GridSearchCV` – Hyperparameter tuning
  - `train_test_split`, `accuracy_score` – Model validation and evaluation

---

## 🧠 Machine Learning Model

We used `DecisionTreeClassifier` from scikit-learn. Here's a breakdown:

- **Hyperparameter Tuning:** Performed using `GridSearchCV` to find the best combination of:
  - `max_depth`
  - `min_samples_split`
  - `criterion`
- **Model Training:** The model was trained on a training set split from the data.
- **Model Evaluation:** Accuracy score was calculated on the test set.

📈 **Final Accuracy:** `97.36%`

---

## 📊 Exploratory Data Analysis

- Created a **correlation heatmap** to understand feature relationships.
- Visualized species distribution using countplots and scatter plots.
- Plotted the **Decision Tree** using `plot_tree()` to see how the model makes decisions.

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/Evertte/Iris-Flower-Classification-DecisionTree.git
cd Iris-Flower-Classification-DecisionTree
```

### Install Required Libraries

```bash
pip install pandas scikit-learn seaborn matplotlib
```

### Run the Project

You can run the project in a Jupyter notebook or a Python script:
```bash
jupyter notebook
```
or  
```bash
python decision_tree_iris.py
```

---

## 📁 File Structure

```
Iris-Flower-Classification-DecisionTree/
│
├── iris.csv                         # Dataset
├── decision_tree_iris.ipynb         # Main notebook
├── decision_tree_iris.py            # Python script (optional)
├── README.md                        # Project documentation
└── images/                          # Visualizations (heatmap, decision tree, etc.)
```

---

## 💡 Future Work

- Add support for other classifiers (e.g., Random Forest, SVM)
- Create a simple web UI for prediction using Streamlit
- Add feature importance plot

---

## 👨‍💻 Author

**Evertte**  
GitHub: [@Evertte](https://github.com/Evertte)

---

⭐ **If you found this helpful, please give it a star!**
```
