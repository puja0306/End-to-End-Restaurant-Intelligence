# 🍽️ End-to-End Restaurant Intelligence: Prediction, Recommendation & Spatial Analytics

An end-to-end data science and machine learning pipeline built to extract actionable insights, predict restaurant aggregate ratings, recommend restaurants based on user preferences, classify cuisines, and perform spatial market analysis.

---

## 📌 Project Overview

This project consists of 4 primary modules:
1. **Task 1: Rating Prediction (Regression)**
   - Preprocessed restaurant data (handling missing values, one-hot encoding, feature scaling).
   - Trained and compared **Linear Regression**, **Decision Tree**, and **Random Forest Regressors**.
   - Evaluated models using MAE, MSE, RMSE, and $R^2$ score, followed by feature importance extraction.

2. **Task 2: Content-Based Restaurant Recommendation Engine**
   - Engineered combined text metadata profiles (Cuisines, City, Price Range, Delivery status).
   - Implemented a **TF-IDF Vectorizer** and calculated **Cosine Similarity** to match user queries with top-rated restaurant alternatives.

3. **Task 3: Cuisine Classification**
   - Built a multi-class classification model using **Logistic Regression** and **Random Forest Classifier**.
   - Categorized restaurants into their primary cuisine types and evaluated precision, recall, F1-score, and confusion matrices.

4. **Task 4: Location-Based Spatial Analysis**
   - Mapped restaurant geographic density and clusters using **Folium** interactive maps.
   - Evaluated performance metrics across cities and localities (e.g., average rating, price tier distributions).

---

## 🛠️ Tech Stack & Libraries

- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Machine Learning:** `scikit-learn`
- **Visualization:** `matplotlib`, `seaborn`, `folium`
- **Environment:** Google Colab / Jupyter Notebook

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone [https://github.com/your-username/End-to-End-Restaurant-Intelligence.git](https://github.com/your-username/End-to-End-Restaurant-Intelligence.git)
   cd End-to-End-Restaurant-Intelligence

