# 🍽️ Restaurant Cuisine Classification

[![Python Version](https://img.shields.io/badge/Python-3.7%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

---

<p align="center">
  <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=800&q=80" alt="Restaurant Image" width="800" />
</p>

## 🚀 Overview

> A sleek Jupyter Notebook project for exploring, visualizing, and classifying restaurant cuisines using modern ML pipelines.

---

## 📑 Table of Contents

1. [🗄️ Dataset](#🗄️-dataset)
2. [▶️ Usage](#▶️-usage)
3. [📂 Structure](#📂-structure)
4. [🛠️ Core Functions](#🛠️-core-functions)
5. [📊 Results](#📊-results)
6. [📬 Contact](#📬-contact)

---

## ✨ Features

* **🔍 Data Exploration & Cleaning**: Quick insights into dataset shape, nulls, and value distributions.
* **📈 Visualization**: Beautiful charts—top cuisines bar plots and correlation heatmaps.
* **🔄 Preprocessing Pipelines**: Label encoding, one-hot encoding, and scaling through scikit-learn `Pipeline`.
* **🤖 Multiple Models**: Try Logistic Regression, Random Forest, and Gradient Boosting with minimal code changes.
* **🏆 Evaluation**: Built-in metrics (Accuracy, Precision, Recall, F1) and confusion matrix display.

---

## 🗄️ Dataset

Download or place `Dataset.csv` in the project root. Sample schema:

| Field            | Description                      |
| ---------------- | -------------------------------- |
| `Restaurant ID`  | 🔑 Unique identifier             |
| `Name`           | 🏷️ Restaurant name              |
| `Cuisine`        | 🍜 Primary cuisine type          |
| *Other features* | ⭐ Ratings, location, price, etc. |

> 💡 **Tip:** Use Google Colab for quick uploads if you’re working online.

---

## ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/restaurant-cuisine-classification.git
cd restaurant-cuisine-classification

# Setup virtual env
python3 -m venv venv
source venv/bin/activate

# Install deps
pip install -r requirements.txt
```

---

## ▶️ Usage

### 🌐 Jupyter Notebook

1. Launch `Task3.ipynb` in Jupyter or Colab.
2. Run cells sequentially.
3. Visualize results inline.

### 🖥️ Script Mode

```bash
python scripts/restaurant_analysis.py path/to/Dataset.csv
```

---

## 📂 Structure

```
├── README.md
├── Dataset.csv
├── Task3.ipynb
└── scripts/
    └── restaurant_analysis.py
```

---

## 🛠️ Core Functions

| Function                        | Purpose                                       |
| ------------------------------- | --------------------------------------------- |
| `load_and_explore_data(path)`   | Load CSV & display overview                   |
| `clean_and_engineer_features()` | Handle missing data & extract primary cuisine |
| `visualize_data(df)`            | Generate bar charts & heatmaps                |
| `build_models(X, y)`            | Setup & train ML pipelines                    |
| `evaluate_models(models, X, y)` | Compute metrics & plot confusion matrices     |

---

## 📊 Results

**Best Model:** 🏅 `RandomForestClassifier`
**Accuracy:** `0.82`  🔢
**Precision:** `0.79`  🎯
**Recall:** `0.77`  📣
**F1-Score:** `0.78`  🥇

*(Update with your experimental results.)*

---

## 🤝 Contributing

1. **Fork** the repo
2. **Branch**: `git checkout -b feature/YourFeature`
3. **Commit**: `git commit -m "Add new feature"`
4. **Push**: `git push origin feature/YourFeature`
5. Open a **Pull Request**

---


## 📬 Contact

**SAMYUKTHA SASIKUMAR** • [samyukthasasikumar0061@gmail.com](mailto:samyukthasasikumar0061@gmail.com) • [GitHub: SAMYUKTHACS07](https://github.com/SAMYUKTHACS07)

*Made with ❤️ and ☕*

