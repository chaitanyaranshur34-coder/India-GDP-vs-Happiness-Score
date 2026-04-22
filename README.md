# 📊 India's GDP vs Happiness Score

## 📌 Overview

This project explores the relationship between **GDP per capita** and **happiness (life satisfaction)** using machine learning models. The goal is to understand whether economic growth correlates with human well-being and to demonstrate basic regression techniques.

The project uses real-world data and applies:

* Linear Regression
* K-Nearest Neighbors (KNN) Regression

---

## 🎯 Objectives

* Analyze the relationship between GDP per capita and happiness score
* Build predictive models using regression techniques
* Compare simple vs non-linear approaches
* Visualize patterns in socio-economic data

---

## 📂 Dataset

The dataset is sourced from:

* OECD life satisfaction data
* GDP per capita data

Primary features:

* **GDP per capita (USD)**
* **Life satisfaction score**

---

## 🛠️ Technologies Used

* Python (>= 3.7)
* NumPy
* Pandas
* Matplotlib
* Scikit-learn (>= 1.0.1)

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/gdp-vs-happiness.git
cd gdp-vs-happiness
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

Run the Jupyter Notebook:

```bash
jupyter notebook "India's GDP vs Happiness Score.ipynb"
```

---

## 📈 Methodology

### 1. Data Preparation

* Load dataset using Pandas
* Extract GDP per capita as feature (X)
* Extract life satisfaction as target (y)

### 2. Linear Regression Model

* Fit a linear model to understand direct correlation
* Visualize regression line

### 3. K-Nearest Neighbors (KNN)

* Apply non-linear regression
* Capture local patterns in data

---

## 📊 Results

* Linear regression shows a general positive correlation between GDP and happiness
* KNN provides a more flexible model that adapts to local variations

---

## 📉 Visualization

The project includes plots showing:

* Scatter plot of GDP vs happiness
* Regression line (Linear Regression)
* Predictions comparison

---

## 🧠 Key Insights

* Higher GDP generally correlates with higher happiness, but not perfectly
* Economic growth alone does not fully explain well-being
* Non-linear models may better capture real-world relationships

---

## 🔮 Future Improvements

* Include more features (health, education, inequality)
* Use advanced models (Random Forest, Gradient Boosting)
* Perform country-specific analysis (e.g., India-focused trends)

---

## 🤝 Contributing

Contributions are welcome. Please fork the repository and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👤 Author

Chaitanya Ranshur

---

## ⭐ Acknowledgements

* Dataset inspired by real-world economic and happiness studies
* Scikit-learn documentation for model implementation
