# AI-for-climate-action-SDG-13
This AI-powered project aims to support SDG 13: Climate Action by predicting Kenya's CO₂ emissions using socio-economic indicators and machine learning.

# 🇰🇪 Forecasting CO₂ Emissions in Kenya using Machine Learning

## 🎯 Objective

To forecast carbon dioxide emissions in Kenya using a Linear Regression model and open data. The model supports decision-making for climate policies and sustainable development.

---

## 🌱 Background & Motivation

Climate change is a pressing global challenge, and Kenya is particularly vulnerable to its impacts. Accurate forecasting of CO₂ emissions is crucial for policymakers to design effective climate action strategies. This project leverages open data and machine learning to provide actionable insights for SDG 13 (Climate Action).

## 📊 Data Sources

- World Bank Open Data
- Kenya National Bureau of Statistics
- Other reputable public datasets (see `data/` folder for details)

The dataset includes socio-economic indicators such as GDP, energy consumption, population, and historical CO₂ emissions from 2005 to 2019.

## ⚙️ Usage

1. **Clone the repository and install dependencies** (see below).
2. **Explore the data and model**: Use the Jupyter Notebook in `scripts/` for exploratory data analysis and model prototyping.
3. **Train and evaluate the model**: Run the Python scripts to train the Linear Regression model and assess its performance.
4. **Interactive predictions**: Launch the Streamlit app (`app.py`) to make predictions based on user input and visualize results.

---

## 📁 Project Structure

- `data/`: CSV file containing training data (2005–2019)
- `scripts/`: Python script for training and evaluating the model
- `app.py`: Streamlit web app for interactive prediction
- `images/`: Screenshots of demo and visualizations
- `requirements.txt`: Dependencies

---

## 🧠 Tech Stack

- Python (Scikit-learn, Pandas, Matplotlib, Streamlit)
- Jupyter Notebook for EDA and model prototyping
- GitHub for version control and sharing

---

## 🖥️ Screenshots

### 📈 Model Evaluation (R² Score, MAE)
![Model Evaluation](images/Model%20Evaluation%20(R²%20Score,%20MAE).png)

### 🌍 Historical CO₂ Emissions in Kenya
![Emission Chart](images/Historical%20CO₂%20Emissions%20in%20Kenya.png)

---

## 🔍 How to Run

Clone the repo and install dependencies:

```bash
git clone https://github.com/KERAMA-sys/AI-for-climate-action-SDG-13.git
```

