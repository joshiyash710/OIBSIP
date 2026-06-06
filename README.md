<h1 align="center">
  <img src="https://img.shields.io/badge/Oasis%20Infobyte-Data%20Science%20Internship-FFD700?style=for-the-badge&labelColor=1a1a2e" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Data%20Science-orange?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Language-Python%203.x-blue?style=flat-square&logo=python" />
  <img src="https://img.shields.io/badge/Tasks%20Completed-5%20%2F%205-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Submitted-success?style=flat-square" />
  <img src="https://img.shields.io/badge/Internship-AICTE%20Approved-blueviolet?style=flat-square" />
</p>

<p align="center">
  Official task submission repository for the <strong>Oasis Infobyte Data Science Internship</strong>.<br/>
  Submitted by <strong>Yash Joshi</strong> | DEPSTAR, CHARUSAT University
</p>

---

## 👨‍💻 Intern Details

| Field | Details |
|-------|---------|
| **Name** | Yash Joshi |
| **College** | DEPSTAR, CHARUSAT University, Gujarat |
| **Branch** | B.Tech — Information Technology |
| **Batch** | 2023–27 (Final Year) |
| **CGPA** | 9.25 / 10 |
| **Email** | joshiyash710@gmail.com |
| **LinkedIn** | [yashjoshi710](https://www.linkedin.com/in/yashjoshi710) |
| **GitHub** | [joshiyash710](https://github.com/joshiyash710) |
| **Portfolio** | [joshiyash710.github.io](https://joshiyash710.github.io) |

## 📁 Repository Structure

---

## 📌 Data Science Task Overview

> ✅ Minimum **3 tasks** required for internship completion.

---

### 🔷 Task 1 — Iris Flower Classification

**Objective:** Train a machine learning model to classify iris flowers into three species — *Setosa*, *Versicolor*, and *Virginica* — based on their sepal and petal measurements.

**Approach:**
- Loaded and explored the Iris dataset (150 samples, 4 features)
- Performed EDA: pairplots, correlation heatmap, class distribution
- Trained and compared classifiers: Logistic Regression, K-Nearest Neighbors, Decision Tree, Random Forest
- Evaluated using Accuracy, Classification Report, Confusion Matrix

**Tech Stack:** `Python` · `Scikit-learn` · `Pandas` · `Matplotlib` · `Seaborn`

**Dataset:** [Kaggle — Iris Dataset](https://www.kaggle.com/datasets/arshid/iris-flower-dataset)

---

### 🔷 Task 2 — Unemployment Analysis with Python

**Objective:** Analyze the sharp rise in unemployment rates — particularly during the COVID-19 pandemic — using exploratory data analysis and visualization.

**Approach:**
- Loaded region-wise unemployment data across Indian states
- Time-series analysis of unemployment rate trends before and during COVID-19
- State-wise and region-wise comparative visualizations
- Identified peak unemployment periods and recovery patterns

**Tech Stack:** `Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Plotly`

**Dataset:** [Kaggle — Unemployment in India](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)

---

### 🔷 Task 3 — Car Price Prediction with Machine Learning

**Objective:** Build a regression model to predict the selling price of a used car based on features like brand, fuel type, year of manufacture, transmission, and mileage.

**Approach:**
- Data cleaning: handled missing values, encoded categorical features (fuel, seller type, transmission)
- Feature engineering: derived car age from manufacturing year
- Trained Linear Regression and Random Forest Regressor models
- Compared models on MAE, RMSE, and R² Score

**Tech Stack:** `Python` · `Scikit-learn` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn`

**Dataset:** [Kaggle — Car Price Prediction](https://www.kaggle.com/datasets/vijayaadithyanvg/car-price-predictionused-cars)

---

### 🔷 Task 4 — Email Spam Detection with Machine Learning

**Objective:** Build an NLP-based classifier to detect and categorize emails as spam or non-spam (ham) using machine learning.

**Approach:**
- Text preprocessing pipeline: lowercasing, punctuation removal, stopword removal, stemming
- Feature extraction using TF-IDF Vectorization
- Trained Multinomial Naive Bayes, Logistic Regression, and SVM classifiers
- Evaluated on Accuracy, Precision, Recall, F1-Score, and Confusion Matrix
- Achieved ~97%+ accuracy with Naive Bayes

**Tech Stack:** `Python` · `Scikit-learn` · `NLTK` · `Pandas` · `Matplotlib` · `Seaborn`

**Dataset:** [Kaggle — SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---

### 🔷 Task 5 — Sales Prediction Using Python

**Objective:** Predict future product sales based on advertising spend across TV, Radio, and Newspaper channels using regression analysis.

**Approach:**
- Performed EDA: distribution plots, pairplots, correlation heatmap
- Analyzed feature-wise impact of advertising channels on sales
- Trained Linear Regression model on the Advertising dataset
- Evaluated using MAE, MSE, RMSE, and R² Score (~0.89)
- Residual analysis and Actual vs Predicted visualization
- Built custom prediction for any new advertising budget input

**Tech Stack:** `Python` · `Scikit-learn` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn`

**Dataset:** [Kaggle — Advertising Dataset](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)

---

## 📊 Results Summary

| # | Task | Best Model | Key Metric |
|---|------|-----------|------------|
| 1 | Iris Flower Classification | Random Forest | Accuracy ~98% |
| 2 | Unemployment Analysis | EDA / Visualization | Trend & pattern insights |
| 3 | Car Price Prediction | Random Forest Regressor | R² Score ~0.88 |
| 4 | Email Spam Detection | Multinomial Naive Bayes | Accuracy ~97% |
| 5 | Sales Prediction | Linear Regression | R² Score ~0.89 |

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/joshiyash710/OIBSIP.git
cd OIBSIP
```

### 2. Set Up Virtual Environment
```bash
python -m venv venv

# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```

Navigate to the task folder and open the `.ipynb` file.

---

## 🛠️ Core Dependencies

```txt
numpy>=1.24.0
pandas>=2.0.0
matplotlib>=3.7.0
seaborn>=0.12.0
scikit-learn>=1.3.0
nltk>=3.8.0
plotly>=5.15.0
jupyter>=1.0.0
notebook>=7.0.0
```

Install all at once:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn nltk plotly jupyter notebook
```

---

## 📋 Submission Checklist

- [x] Task 1 — Iris Flower Classification
- [x] Task 2 — Unemployment Analysis
- [x] Task 3 — Car Price Prediction
- [x] Task 4 — Email Spam Detection
- [x] Task 5 — Sales Prediction
- [x] GitHub repository named **OIBSIP**
- [x] Demo videos posted on LinkedIn with `#oasisinfobyte`
- [x] Peer evaluation completed (commented on 2+ intern videos)

---

## 🏷️ LinkedIn Hashtags Used

`#oasisinfobyte` · `#oasisinfobytefamily` · `#internship` · `#datascience` · `#python` · `#machinelearning` · `#campusambassador`

---

## 🤝 Acknowledgements

- **[Oasis Infobyte](https://oasisinfobyte.com)** — for the AICTE-approved internship program and structured task framework
- **Scikit-learn & Python Community** — for open-source ML tools
- **CHARUSAT University, DEPSTAR** — for continuous academic support

---

<p align="center">
  <strong>Yash Joshi</strong> · B.Tech IT · DEPSTAR, CHARUSAT · 2025<br/>
  <a href="https://www.linkedin.com/in/yashjoshi710">LinkedIn</a> ·
  <a href="https://github.com/joshiyash710">GitHub</a> ·
  <a href="https://joshiyash710.github.io">Portfolio</a>
</p>


---

