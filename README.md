<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0F2027,50:203A43,100:2C5364&height=180&section=header&text=Indian%20Used%20Car%20Price%20Prediction&fontSize=32&fontColor=D4AF37&animation=fadeIn&fontAlignY=45&desc=A%20Machine%20Learning%20Approach%20to%20Automotive%20Resale%20Valuation&descAlignY=68&descSize=14&descColor=E8E8E8"/>

<br/>

<img src="https://img.shields.io/badge/Python-0F2027?style=flat-square&logo=python&logoColor=D4AF37"/>
<img src="https://img.shields.io/badge/Scikit--Learn-203A43?style=flat-square&logo=scikitlearn&logoColor=D4AF37"/>
<img src="https://img.shields.io/badge/Pandas-2C5364?style=flat-square&logo=pandas&logoColor=D4AF37"/>
<img src="https://img.shields.io/badge/NumPy-0F2027?style=flat-square&logo=numpy&logoColor=D4AF37"/>
<img src="https://img.shields.io/badge/Status-Completed-2C5364?style=flat-square&logoColor=D4AF37"/>
<img src="https://img.shields.io/badge/License-MIT-D4AF37?style=flat-square"/>

<br/><br/>

<a href="https://github.com/shahrishabh1513-jsk/Indian-Used-Car-Price-Prediction/blob/main/Indian_Used_Car_Price_Prediction.pdf"><b>📄 Project Report</b></a>
&nbsp;·&nbsp;
<a href="https://github.com/shahrishabh1513-jsk/Indian-Used-Car-Price-Prediction/blob/main/Indian_Used_Car_Price_Prediction.ipynb"><b>📒 Notebook</b></a>
&nbsp;·&nbsp;
<a href="https://github.com/shahrishabh1513-jsk/Indian-Used-Car-Price-Prediction"><b>⭐ Star This Repo</b></a>

</div>

<br/>

<table align="center">
<tr>
<td align="center" width="20%"><sub>BEST MODEL</sub><br><b>Random Forest</b></td>
<td align="center" width="20%"><sub>MODELS COMPARED</sub><br><b>3</b></td>
<td align="center" width="20%"><sub>PIPELINE STAGES</sub><br><b>7</b></td>
<td align="center" width="20%"><sub>LANGUAGE</sub><br><b>Python 3.10</b></td>
<td align="center" width="20%"><sub>DELIVERABLE</sub><br><b>Full Report (PDF)</b></td>
</tr>
</table>

<br/>

<p align="center">
<a href="#preview">Preview</a> &nbsp;|&nbsp;
<a href="#project-overview">Overview</a> &nbsp;|&nbsp;
<a href="#objectives">Objectives</a> &nbsp;|&nbsp;
<a href="#tech-stack">Tech Stack</a> &nbsp;|&nbsp;
<a href="#machine-learning-workflow">Workflow</a> &nbsp;|&nbsp;
<a href="#exploratory-data-analysis">EDA</a> &nbsp;|&nbsp;
<a href="#machine-learning-models">Models</a> &nbsp;|&nbsp;
<a href="#installation">Installation</a> &nbsp;|&nbsp;
<a href="#connect">Connect</a>
</p>

<hr/>

## Preview

<div align="center">

<a href="https://github.com/shahrishabh1513-jsk/Indian-Used-Car-Price-Prediction" target="_blank">
<img src="https://opengraph.githubassets.com/64923ef7ee6d56d22bf514165f7d3fa4366ca14eeb62780400367cc28bf4c4e7/shahrishabh1513-jsk/Indian-Used-Car-Price-Prediction" width="80%" style="border-radius:8px; border: 1px solid #2C5364;"/>
</a>

<sub>Click to open the repository on GitHub</sub>

</div>

<hr/>

## Project Overview

The Indian used car market is one of the fastest-growing segments of the automobile industry. Accurately pricing a second-hand vehicle depends on a combination of factors — manufacturing year, fuel type, transmission, kilometers driven, ownership history, and brand value.

This project builds a **machine learning model** to predict the resale price of a used car from historical automobile data, covering the complete lifecycle: **data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction.**

| | |
|---|---|
| **Domain** | Automotive Resale · Regression Problem |
| **Approach** | Supervised Machine Learning |
| **Best Model** | Random Forest Regressor |
| **Techniques** | EDA · Feature Engineering · Model Comparison |

<hr/>

## Objectives

<table>
<tr>
<td width="50%" valign="top">

**Core goals**
- Predict the resale price of used cars
- Perform comprehensive exploratory data analysis
- Engineer meaningful features from raw data

</td>
<td width="50%" valign="top">

**Evaluation goals**
- Compare multiple machine learning models
- Select the most accurate regression algorithm
- Build a deployment-ready prediction pipeline

</td>
</tr>
</table>

<hr/>

## Tech Stack

| Category | Technology | Purpose |
|---|---|---|
| **Language** | Python 3.10 | Core programming language |
| **Data Analysis** | Pandas, NumPy | Data cleaning & manipulation |
| **Visualization** | Matplotlib, Seaborn | Charts and EDA visuals |
| **Machine Learning** | Scikit-Learn | Model training & evaluation |
| **Development** | Jupyter Notebook, VS Code | Experimentation & coding |

<hr/>

## Project Structure

<details>
<summary><b>View folder structure</b></summary>

```bash
Indian-Used-Car-Price-Prediction/
│
├── dataset/
│   └── used_car_dataset.csv          # Raw automobile dataset
│
├── notebooks/
│   └── Indian_Used_Car_Price_Prediction.ipynb   # Full source code
│
├── reports/
│   └── Indian_Used_Car_Price_Prediction.pdf       # Complete project report
│
├── models/
│   └── random_forest_model.pkl                      # Trained best model
│
├── images/
│   └── graphs.png                                      # EDA visualizations
│
├── requirements.txt                                        # Dependencies
├── README.md                                                  # Documentation
└── LICENSE
```

</details>

<hr/>

## Machine Learning Workflow

<div align="center">

**Raw Dataset** → **Data Cleaning** → **Exploratory Data Analysis** → **Feature Engineering** → **Train-Test Split** → **Model Training** → **Evaluation** → **Price Prediction**

</div>

<hr/>

## Exploratory Data Analysis

EDA was performed to understand the dataset's structure and relationships before model training.

| Finding | Insight |
|---|---|
| Vehicle age | Strongest negative relationship with selling price |
| Kilometers driven | Fewer kilometers correlate with higher resale value |
| Fuel type | Diesel vehicles retain higher resale prices than petrol |
| Brand tier | Premium brands depreciate more slowly |
| Transmission | Automatic transmission vehicles are generally priced higher |

<hr/>

## Feature Engineering

<table>
<tr>
<td width="50%" valign="top">

**Preprocessing applied**
- Missing value handling
- Duplicate removal & outlier detection
- Label Encoding & One-Hot Encoding
- Feature scaling & train-test split

</td>
<td width="50%" valign="top">

**Engineered features**
- Car Age
- Brand Category
- Vehicle Usage

</td>
</tr>
</table>

<hr/>

## Machine Learning Models

| Model | Performance |
|---|---|
| Linear Regression | Baseline |
| Decision Tree Regressor | Moderate accuracy |
| **Random Forest Regressor** | **Best performance** |

**Final model — Random Forest Regressor**, selected for its highest prediction accuracy, lowest Mean Absolute Error (MAE), effective handling of nonlinear relationships, and robustness against overfitting.

**Evaluation metrics:** Mean Absolute Error (MAE) · Mean Squared Error (MSE) · Root Mean Squared Error (RMSE) · R² Score

<hr/>

## Features

- Data cleaning pipeline
- Exploratory data analysis
- Feature engineering
- Multiple regression models compared
- Best model selection
- Prediction-ready pipeline
- Easy to deploy

<hr/>

## Sample Workflow

```
Input: Brand · Year · Fuel Type · Transmission · Kilometers Driven · Owner
                              │
                              ▼
                  Machine Learning Model
                              │
                              ▼
                  Predicted Selling Price
```

<hr/>

## Repository Resources

| Resource | Description |
|---|---|
| 📄 Project Report | Complete methodology and analysis |
| 📒 Jupyter Notebook | Full source code |
| 📊 Dataset | Used car dataset |
| 🤖 Trained Model | Random Forest model |

<hr/>

## Installation

```bash
# Clone the repository
git clone https://github.com/shahrishabh1513-jsk/Indian-Used-Car-Price-Prediction.git

# Move into the project folder
cd Indian-Used-Car-Price-Prediction

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

<hr/>

## Future Improvements

- [ ] Streamlit web application
- [ ] Flask REST API
- [ ] Hyperparameter tuning
- [ ] XGBoost & LightGBM
- [ ] Real-time market data integration
- [ ] Docker deployment
- [ ] Cloud deployment (Render / Railway / Azure)

<hr/>

## Learning Outcomes

Data Preprocessing · Exploratory Data Analysis · Feature Engineering · Regression Algorithms · Model Evaluation · Performance Comparison · End-to-End ML Workflow

<hr/>

## Connect

<div align="center">

**Rishabh Alpeshabhai Shah**

<a href="https://rishabh-shah-portfolio.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-0F2027?style=flat-square&logo=netlify&logoColor=D4AF37"/></a>
<a href="https://www.linkedin.com/in/rishabh-alpeshabhai-shah-91b9072a6/"><img src="https://img.shields.io/badge/LinkedIn-203A43?style=flat-square&logo=linkedin&logoColor=D4AF37"/></a>
<a href="mailto:shahrishu1515@gmail.com"><img src="https://img.shields.io/badge/Email-2C5364?style=flat-square&logo=gmail&logoColor=D4AF37"/></a>
<a href="https://github.com/shahrishabh1513-jsk"><img src="https://img.shields.io/badge/GitHub-0F2027?style=flat-square&logo=github&logoColor=D4AF37"/></a>

</div>

<hr/>

<div align="center">

<sub>If this project was useful, consider giving it a star.</sub>

<img src="https://komarev.com/ghpvc/?username=indian-used-car-price-prediction&label=Repository%20Views&color=2C5364&style=flat-square"/>

<br/><br/>

<sub>Built with Python & Machine Learning — Rishabh A. Shah</sub>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2C5364,50:203A43,100:0F2027&height=80&section=footer"/>

</div>
