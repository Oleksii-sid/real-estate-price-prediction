# 🏠 Real Estate Price Prediction & Market Analysis

[![Python](https://shields.io)](https://python.org)
[![Scikit-Learn](https://shields.io)](https://scikit-learn.org)
[![License: MIT](https://shields.io)](https://opensource.org)

## 📌 Project Overview
An end-to-end Machine Learning and Data Science project focused on predicting real estate prices based on structural, geographical, and economic features. This project demonstrates how data-driven insights can assist real estate agencies and investors in evaluating property values accurately, mitigating financial risks, and identifying underpriced assets.

## 🎯 Business Value
* **Accurate Valuations:** Reduces human error in real estate appraisal by implementing robust regression models.
* **Investment Optimization:** Enables automated filtering to catch high-potential real estate deals instantly.
* **Feature Importance Analysis:** Highlights which factors (e.g., location, square footage, building age) drive property costs the most.

## 🛠️ Tech Stack & Engineering Pipeline
* **Language:** Python 3.10+
* **Data Processing & EDA:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn (Linear Regression, Ridge/Lasso, Random Forest Regressor)
* **Environment:** Jupyter Notebook, Git

### 🔧 The ML Pipeline:
1. **Data Engineering & Cleaning:** Handled missing values, treated statistical outliers using the IQR (Interquartile Range) method, and performed one-hot encoding for categorical location features.
2. **Exploratory Data Analysis (EDA):** Analyzed multi-collinearity via correlation matrices (Pearson correlation) to drop redundant features.
3. **Feature Selection:** Selected top predictive features using variance thresholds and recursive feature elimination.
4. **Model Training & Hyperparameter Tuning:** Compared multiple regression models and optimized performance via Grid Search Cross-Validation (GridSearchCV).
5. **Evaluation:** Evaluated models using R² score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## 📊 Key Results & Key Performance Indicators (KPIs)
* **Model Accuracy:** The final optimized model (Random Forest Regressor) achieved an **R² score of 0.89+**, explaining over 89% of price variance.
* **Error Reduction:** Hyperparameter tuning reduced the Mean Absolute Error (MAE) by **14%** compared to the baseline Linear Regression model.
* **Insight:** Proximity to the city center and total living area were identified as the strongest price drivers.

## 📂 Project Structure
```text
real-estate-price-prediction/
│
├── data/                  # Raw and preprocessed CSV datasets
├── notebooks/             # real_estate_analysis.ipynb (EDA & Model Training)
├── models/                # Saved serialized models (.pkl) for production deployment
├── screenshots/           # Data visualization plots and performance charts
├── README.md              # Project documentation
└── main.py                # Production script for inference
```

## 🚀 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com
   cd real-estate-price-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the production inference script:
   ```bash
   python main.py
   ```

## 📈 Future Roadmap
- [ ] Containerize the prediction service using **Docker**.
- [ ] Build a lightweight web UI dashboard using **Streamlit** or **FastAPI**.
- [ ] Integrate real-time real estate data scraping via Cron Jobs.

## 👤 Author
* **Oleksii Sidenko**
* GitHub: [@Oleksii-sid](https://github.com/Oleksii-sid)
