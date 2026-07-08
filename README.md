# 🎮 SteamScope

### End-to-End Data Science Pipeline for Steam Market Analytics, Time Series Forecasting and Machine Learning

<p align="center">

<img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Random%20Forest-Forecasting-success?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Time%20Series-Forecasting-8A2BE2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/EDA-Visualization-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/License-MIT-black?style=for-the-badge"/>

</p>

<p align="center">

<b>Data Science project for analyzing Steam market dynamics using Machine Learning, Time Series Forecasting and Economic Analytics.</b>

Developed as an end-to-end pipeline covering exploratory analysis, feature engineering, predictive modeling, synthetic market simulation, forecasting and visualization.

</p>

---

# 📌 Overview

Steam is the largest digital game distribution platform in the world, hosting thousands of games with different pricing strategies, promotional campaigns and player engagement dynamics.

This project combines **Exploratory Data Analysis (EDA)**, **Machine Learning**, **Time Series Forecasting**, and **Market Analytics** to investigate how pricing, promotions and temporal effects influence player activity.

The repository is divided into two complementary modules.

- **Steam Analytics** – Exploratory analysis, feature engineering and predictive modeling.
- **Steam Time Series** – Simulation of Concurrent Users (CCU), demand elasticity, retention analysis and forecasting.

The project follows an end-to-end Data Science workflow, from data preparation and feature engineering to predictive modeling and publication-quality visualizations.

---

# 🎯 Objectives

- Analyze Steam market dynamics
- Explore pricing strategies
- Study promotional campaigns
- Forecast Concurrent Users (CCU)
- Analyze player retention
- Estimate price elasticity of demand
- Engineer temporal features
- Compare Machine Learning models
- Produce publication-quality visualizations

---

# 🧠 Project Pipeline

```text
                           Steam Market Dataset
                                    │
                                    ▼
                       Data Cleaning & Validation
                                    │
                ┌───────────────────┴───────────────────┐
                ▼                                       ▼
    Exploratory Data Analysis                 Time Series Analysis
                │                                       │
                ▼                                       ▼
       Feature Engineering             Lag Features & Rolling Statistics
                │                                       │
                ▼                                       ▼
        Machine Learning                  Time Series Forecasting
                │                                       │
                └───────────────────┬───────────────────┘
                                    ▼
                       Comparative Evaluation
                                    │
                                    ▼
 Forecasting • Elasticity • Retention • Publication-quality Figures
```

---

# 📊 Project Modules

## 🎮 Steam Analytics

This module investigates the Steam marketplace using descriptive statistics, visualization and machine learning.

### Main Tasks

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Predictive Modeling
- Comparative Evaluation

---

## 📈 Steam Time Series

The second module investigates temporal dynamics of Steam games through synthetic market simulations.

Topics include

- Synthetic Concurrent Users (CCU)
- Steam Summer Sale simulation
- Steam Winter Sale simulation
- Promotional campaigns
- Player retention analysis
- Price elasticity of demand
- Lag Features
- Rolling Statistics
- Random Forest forecasting

---

# 📊 Dataset

The project uses Steam market information containing metadata about games and synthetic temporal player activity.

| Feature | Description |
|----------|-------------|
| Games | Steam titles |
| Price | Game price |
| Genre | Game category |
| Publisher | Company responsible for publication |
| Reviews | Community feedback |
| Concurrent Users (CCU) | Simulated player activity |
| Promotion | Steam sale events |
| Release Date | Game launch date |

---

# ⚙️ Feature Engineering

Several variables were engineered to improve predictive performance.

| Feature | Description |
|----------|-------------|
| CCU Lag 1 | Previous day's concurrent users |
| CCU Lag 7 | Weekly lag |
| Rolling Mean | Moving average of player activity |
| Rolling Std | Weekly volatility |
| Weekend Indicator | Weekend effect |
| Promotion Indicator | Steam Sale events |
| Price Discount | Promotional discount |
| Seasonal Component | Seasonality indicator |

---

# 🤖 Machine Learning Models

| Model | Purpose |
|--------|----------|
| Random Forest Regressor | Forecast Concurrent Users |
| Feature Engineering | Improve prediction |
| Lag Features | Capture temporal dependence |
| Rolling Statistics | Capture local trends |

---

# 📈 Evaluation Metrics

The forecasting models are evaluated using multiple metrics.

| Metric | Purpose |
|----------|----------|
| RMSE | Prediction error |
| MAE | Absolute prediction error |
| MAPE | Percentage prediction error |
| R² Score | Explained variance |

---

# 📷 Visualizations

The project automatically generates several publication-quality figures.

## 📊 Exploratory Data Analysis

<p align="center">
<img src="figures/01_price_distribution.png" width="48%">
<img src="figures/02_games_per_year.png" width="48%">
</p>

<p align="center">
<img src="figures/03_free_vs_paid.png" width="48%">
<img src="figures/04_top_publishers.png" width="48%">
</p>

<p align="center">
<img src="figures/05_top_genres.png" width="48%">
<img src="figures/06_price_vs_reviews.png" width="48%">
</p>

---

## 📈 Time Series & Forecasting

<p align="center">
<img src="steam_figures_timeseries/01_elasticidade_preco.png" width="48%">
<img src="steam_figures_timeseries/02_curva_retencao_jogadores.png" width="48%">
</p>

<p align="center">
<img src="steam_figures_timeseries/03_previsao_ccu_timeseries.png" width="80%">
</p>

---

# 📂 Repository Structure

```text
steam-scope/

│

├── README.md

├── LICENSE

├── requirements.txt

├── steam_analytics.py

├── steam_time_series.py

├── figures/

│   ├── 01_price_distribution.png
│   ├── 02_games_per_year.png
│   ├── 03_free_vs_paid.png
│   ├── 04_top_publishers.png
│   ├── 05_top_genres.png
│   └── 06_price_vs_reviews.png

├── steam_figures_timeseries/

│   ├── 01_elasticidade_preco.png
│   ├── 02_curva_retencao_jogadores.png
│   └── 03_previsao_ccu_timeseries.png

├── models/

└── notebooks/
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/steam-scope.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Steam Analytics

```bash
python steam_analytics.py
```

Run Time Series Analysis

```bash
python steam_time_series.py
```

---

# 🛠 Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Random Forest
- Time Series Forecasting

---

# 📌 Highlights

✅ End-to-End Data Science Pipeline

✅ Steam Market Analytics

✅ Exploratory Data Analysis

✅ Feature Engineering

✅ Machine Learning

✅ Time Series Forecasting

✅ Price Elasticity Analysis

✅ Player Retention Analysis

✅ Random Forest Forecasting

✅ Publication-quality Figures

---

# 🔮 Future Improvements

- XGBoost Forecasting
- LightGBM Forecasting
- Prophet Forecasting
- LSTM Networks
- SHAP Explainability
- Steam Web API Integration
- Interactive Streamlit Dashboard
- Docker Deployment
- MLflow Integration
- Automated Unit Tests
- CI/CD with GitHub Actions

---

# 📚 References

- Steam Market Dataset
- Scikit-Learn Documentation
- Random Forest Regression
- Time Series Forecasting Literature
- Price Elasticity of Demand

---

# 👨‍💻 Author

**Vinícius Nunes Leal**

Physicist | Researcher Scientist
