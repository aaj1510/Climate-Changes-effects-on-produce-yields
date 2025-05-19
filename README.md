# 🌾 ML Crop Yield Predictor

This machine learning project was developed to help farmers understand the **impact of agricultural practices** like pesticide usage, fertilizer application, and organic farming on **crop yields** in the Asia region. Using real-world datasets and predictive modeling, our team aimed to provide a **data-driven tool** to support better decision-making in agriculture.

---

## 📌 Problem Statement

**How can we support farmers in predicting crop yields by understanding how different farming practices affect harvest outcomes?**

---

## 📊 Dataset & Sources

We compiled agricultural datasets from:
- **Kaggle**
- **Government open data portals**
- **Agricultural research sources** across Asia

The datasets included features such as:
- Pesticide usage (quantitative levels)
- Fertilizer types and quantity
- Organic vs conventional farming practices
- Recorded crop yields

---

## 🧠 Methodology

### 📂 Data Processing
- Normalized features to ensure consistency
- Removed outliers after analyzing distribution plots
- Split data into **training** and **testing** sets for model evaluation

### 🤖 ML Models Compared
- **Linear Regression**
- **Polynomial Regression**
- **Gradient Descent Algorithm (custom implementation)**

### 📈 Evaluation Metrics
- **R² Score** (Coefficient of determination)
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Model Intercept/Slopes** for interpretation

---

## 🧪 Results

- Achieved **~90% prediction accuracy** on test data
- Polynomial Regression outperformed Linear in capturing non-linear trends
- Visualized model predictions vs actual yields to identify discrepancies

---

## 📊 Tools & Libraries

| Tool        | Purpose                          |
|-------------|----------------------------------|
| `Python`    | Core language                    |
| `Pandas`    | Data wrangling and preprocessing |
| `Matplotlib`| Plotting and trend analysis      |
| `Seaborn`   | Correlation heatmaps and EDA     |
| `Scikit-learn` | Regression models & metrics   |

---

## 📌 Sample Visuals
![image](https://github.com/user-attachments/assets/c1d3c4c0-c188-4073-9412-33c0d753b266) 
![image](https://github.com/user-attachments/assets/36f1fc38-c1a0-493a-b731-388a675e6bd1)


---

## 💡 Lessons Learned

- **Model selection** has a huge impact on prediction accuracy
- **Data cleaning** and outlier removal significantly improved model performance
- Evaluating models using **multiple metrics** (not just accuracy) helps in selecting the best one
- Hands-on ML experimentation builds a deep understanding of real-world challenges


## 🏁 Future Improvements

- Extend to **multi-crop predictions**
- Deploy as a simple web dashboard for farmer access, such that analysis is easily understood

---

## 📫 Contact

This was one of my first experiences with ML and was fruitful! My background in data analytics and pandas made this much easier. Would recommend to start with Pandas as a beginner.
Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/alainajaiswal/) for collaborations or feedback :D



