# 🚗 Indian Used Car Price Predictor

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
</p>

<h3 align="center">
Predicting the resale value of used cars in India using Machine Learning 🚘
</h3>

<p align="center">
An end-to-end Machine Learning project covering data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction.
</p>

---

# 📌 Project Overview

The Indian used car market is one of the fastest-growing automobile sectors. Pricing a second-hand vehicle accurately depends on multiple factors such as manufacturing year, fuel type, transmission, kilometers driven, ownership history, and brand value.

This project builds a Machine Learning model capable of predicting the market price of a used car using historical automobile data.

---

# 🎯 Objectives

- Predict the resale price of used cars
- Perform comprehensive Exploratory Data Analysis (EDA)
- Engineer meaningful features
- Compare multiple Machine Learning models
- Select the most accurate regression algorithm
- Build a deployment-ready prediction pipeline

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python 3.10 |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn |
| Development | Jupyter Notebook, VS Code |

---

# 📂 Project Structure

```
Indian-Used-Car-Price-Prediction/
│
├── dataset/
│   └── used_car_dataset.csv
│
├── notebooks/
│   └── Indian_Used_Car_Price_Prediction.ipynb
│
├── reports/
│   └── Indian_Used_Car_Price_Prediction.pdf
│
├── models/
│   └── random_forest_model.pkl
│
├── images/
│   └── graphs.png
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

# ⚙️ Machine Learning Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Performance Evaluation
      │
      ▼
Price Prediction
```

---

# 📊 Exploratory Data Analysis

EDA was performed to better understand the dataset before model training.

### Major Findings

✅ Vehicle age has the strongest negative relationship with selling price.

✅ Cars driven fewer kilometers generally command higher resale values.

✅ Diesel vehicles retain higher resale prices than petrol vehicles.

✅ Premium brands experience slower depreciation.

✅ Automatic transmission vehicles are generally priced higher.

---

# 🔧 Feature Engineering

The following preprocessing techniques were applied:

- Missing value handling
- Duplicate removal
- Outlier detection
- Label Encoding
- One-Hot Encoding
- Feature Scaling
- Train-Test Split

Additional engineered features:

- Car Age
- Brand Category
- Vehicle Usage

---

# 🤖 Machine Learning Models

The following regression algorithms were evaluated.

| Model | Performance |
|--------|-------------|
| Linear Regression | Baseline |
| Decision Tree Regressor | Moderate Accuracy |
| Random Forest Regressor | ⭐ Best Performance |

---

# 🏆 Final Model

**Random Forest Regressor**

Reasons for selection:

- Highest prediction accuracy
- Lowest Mean Absolute Error (MAE)
- Handles nonlinear relationships effectively
- Robust against overfitting

---

# 📈 Evaluation Metrics

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 🚀 Features

- Data Cleaning Pipeline
- Exploratory Data Analysis
- Feature Engineering
- Multiple Regression Models
- Model Comparison
- Best Model Selection
- Prediction Ready
- Easy to Deploy

---

# 📷 Sample Workflow

```
Input

Brand
Year
Fuel Type
Transmission
Kilometers Driven
Owner

        │

        ▼

Machine Learning Model

        │

        ▼

Predicted Selling Price
```

---

# 📁 Repository Resources

| Resource | Description |
|----------|-------------|
| 📄 Project Report | Complete methodology and analysis |
| 📒 Jupyter Notebook | Full source code |
| 📊 Dataset | Used car dataset |
| 🤖 Trained Model | Random Forest Model |

---

# 💻 Installation

Clone the repository

```bash
git clone https://github.com/shahrishabh1513-jsk/Indian-Used-Car-Price-Prediction.git
```

Move into the project folder

```bash
cd Indian-Used-Car-Price-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📌 Future Improvements

- Streamlit Web Application
- Flask REST API
- Hyperparameter Tuning
- XGBoost & LightGBM
- Real-time Market Data Integration
- Docker Deployment
- Cloud Deployment (Render / Railway / Azure)

---

# 📚 Learning Outcomes

This project demonstrates:

- Data Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Regression Algorithms
- Model Evaluation
- Performance Comparison
- End-to-End ML Workflow

---

# 🤝 Connect With Me

<p align="center">

<a href="https://github.com/shahrishabh1513-jsk">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/rishabh-alpeshabhai-shah-91b9072a6/">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

</p>

---

# ⭐ Support

If you found this project useful,

⭐ Star this repository

🍴 Fork it

🛠 Contribute to improve it

---

<p align="center">

### 🚘 Built with Python & Machine Learning

**Made with ❤️ by Rishabh A. Shah**

</p>
