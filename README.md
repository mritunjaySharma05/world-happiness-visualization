# 🌍 World Happiness Report 2024 – Data Analysis & Machine Learning

## 📌 Project Overview

This project explores the **World Happiness Report 2024**, using Python to perform **data cleaning**, **exploratory data analysis (EDA)**, and a **linear regression model** to predict a country’s happiness score based on key contributing factors.

> 🎯 **Goal**: Understand what drives happiness across nations and demonstrate applied data science skills relevant for internships in **Data Science**, **Machine Learning**, and **Analytics** roles.

---

## 📁 Dataset

- **Source**: [World Happiness Report 2024](https://worldhappiness.report/)
- **Format**: Excel
- **Key Columns**:
  - `Ladder score` – Overall happiness score
  - `Log GDP per capita`
  - `Social support`
  - `Healthy life expectancy`
  - `Freedom to make life choices`
  - `Generosity`
  - `Perceptions of corruption`
  - `Dystopia + residual`

---

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (LinearRegression, Metrics)

---

## 📊 Exploratory Data Analysis (EDA)

### ✅ Top 10 Happiest Countries

Bar chart showing the top 10 countries by happiness score.

> **Insight**: Clearly shows the happiest countries in the world for 2024.

---

### ✅ GDP vs Happiness

Scatter plot comparing Log GDP per capita with happiness score.

> **Insight**: Shows a positive correlation between a country’s wealth and its happiness.

---

### ✅ Correlation Heatmap

Heatmap showing correlation between all numerical features.

> **Insight**: Helps identify strong predictors of happiness and understand relationships between variables.

---

## 🤖 Machine Learning – Predicting Happiness

### ✅ Linear Regression Model

The target variable is `ladder_score`, predicted using:

- GDP per capita
- Social support
- Healthy life expectancy
- Freedom to make life choices
- Generosity
- Perceptions of corruption
- Dystopia + residual

### 🔍 Evaluation Metrics

| Metric     | Value (example) |
|------------|------------------|
| R² Score   | 0.94 (Strong Fit) |
| MAE        | Low               |
| MSE        | Low               |

> **Conclusion**: The model performs well and explains the majority of the variance in happiness scores.

---

### 📈 Actual vs Predicted

A scatter plot comparing the model's predictions to the actual happiness scores.

> **Insight**: Most points fall close to the diagonal line, showing accurate predictions.

---

### 📌 Feature Importance

The model’s coefficients reveal the most impactful features:

- GDP and Social Support are major contributors
- Corruption and Generosity have smaller influence

---

## 🚀 Skills Demonstrated

✅ Data Cleaning & Preprocessing  
✅ Exploratory Data Analysis (EDA)  
✅ Visualization & Storytelling  
✅ Linear Regression Modeling  
✅ Model Evaluation  
✅ Interpretation of Results  
✅ Working with Real-World Data  

---

## 💼 Internship Relevance

This project demonstrates:

- Real-world problem-solving with data
- Ability to communicate technical and non-technical insights
- Application of ML concepts in a practical, business-relevant way
- Clear, readable code and well-commented notebook

> ✅ Suitable for internship roles like Data Science Intern, ML Intern, Python Developer Intern, or Analytics Intern.

---

## 📎 How to Run

1. Clone this repository or upload the notebook to [Google Colab](https://colab.research.google.com/)
2. Upload the `world-happiness-report-2024.xlsx` file
3. Run each cell in order to see results and predictions

---

## 📬 Contact

Created by **Mritunjay Sharma**  
📧 Email:(mritunjaysharma080505@gmail.com)

🌐 LinkedIn: [add your LinkedIn link]

---

**⭐️ If you found this project helpful, feel free to star the repo!**
