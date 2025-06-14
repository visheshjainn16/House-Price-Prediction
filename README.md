# 🏠 House Price Prediction using Machine Learning

This project predicts **median house prices** in California based on features like income, number of rooms, and population using **Linear Regression**.  
Built as a beginner-level ML project using Python, Pandas, and Scikit-Learn.

---

## 📊 Dataset

- **Source**: California Housing dataset (from Scikit-learn)
- **Target**: `MedHouseVal` (Median House Value)
- **Features Used**:
  - `MedInc`: Median Income
  - `HouseAge`: Median house age
  - `AveRooms`: Average rooms per household
  - `AveBedrms`: Average bedrooms per household
  - `Population`: Block group population
  - `AveOccup`: Average household size
  - `Latitude` and `Longitude`

---

## 🔧 Tools & Libraries

- Python 🐍
- Pandas & NumPy
- Scikit-Learn
- Seaborn & Matplotlib
- Google Colab

---

## 🔥 What I Did (Beginner Roadmap)

1. Loaded and explored the dataset (`.head()`, `.describe()`, `.info()`)
2. Visualized data using histograms, scatterplots, and a correlation heatmap
3. Prepared data (feature-target split, train-test split)
4. Trained a **Linear Regression** model
5. Evaluated using MAE, MSE, and R² score
6. Saved the trained model using `joblib`

---

## ✅ Results

- **R² Score**: `0.58`
- The model performs reasonably well and captures trends based on income and location.

---

## 📁 How to Use

```bash
# Clone this repo
git clone https://github.com/visheshjainn16/House-Price-Prediction.git

# Run the notebook in Google Colab or Jupyter Notebook
