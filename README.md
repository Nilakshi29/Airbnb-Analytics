# 🏙️ NYC Airbnb Classification Project

This project utilizes the **New York City Airbnb Open Data** to build and compare machine learning models for classifying whether an Airbnb listing is located in **Manhattan** or not.

---

## 📁 Dataset

- **Source:** Kaggle (NYC Airbnb Open Data)
- **Features Used:**
  - `latitude`
  - `longitude`
  - `minimum_nights`
  - `number_of_reviews`
  - `reviews_per_month`
  - `availability_365`
- **Target Variable:**
  - `is_manhattan` → 1 if the listing is in Manhattan, 0 otherwise

---

## 🔧 Project Workflow

### 1. Data Preprocessing
- Dropped rows with missing values
- Created a binary target column (`is_manhattan`)
- Applied feature scaling using `StandardScaler`

### 2. Feature Selection
- Used **Recursive Feature Elimination (RFE)** with Logistic Regression to select top 3 features

### 3. Model Training & Evaluation
Trained and evaluated the following classification models:
- ✅ Logistic Regression  
- ✅ K-Nearest Neighbors (KNN)  
- ✅ Decision Tree  
- ✅ Support Vector Machine (SVM)  
- ✅ Random Forest

### 4. Evaluation Metrics
- Accuracy
- Confusion Matrix (using a custom function)
- Accuracy Comparison Plots:
  - Vertical Bar Chart
  - Horizontal Bar Chart
  - Dot Plot

---

## 📊 Visualizations

- 📌 Confusion Matrices for each model
- 📌 Comparative Accuracy Charts with three decimal precision

---

## 🛠️ Tech Stack

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn

---

## ▶️ Getting Started

1. **Clone this repository**  
   ```bash
   git clone https://github.com/yourusername/nyc-airbnb-classification.git
   cd nyc-airbnb-classification
