# Machine Learning Internship - Final Report

This repository contains all tasks completed during my 4-week Machine Learning Internship.

---

## **📅 Week 1: Sales Trends Analysis of a Superstore**
**Goal:** Perform data cleaning, exploratory analysis, and visualization of the Superstore Sales dataset.

### **Tasks:**
- Load and clean dataset (handle missing values, parse dates).
- Perform exploratory analysis to find:
  - Best-selling product category.
  - Highest revenue-generating region.
- Visualize results using bar charts, heatmaps, and line graphs.

### **Key Insights:**
1. **Technology** category had the highest sales.
2. **West** region generated the most revenue.
3. Sales peaked during **holiday seasons**.
4. Discounts increased orders but didn’t always improve profitability.

---

## **📅 Week 2: Student Performance Predictor**
**Goal:** Predict whether a student will pass or fail based on exam scores.

### **Tasks:**
- Define Pass/Fail target variable using a score threshold.
- Train **Logistic Regression** and **Decision Tree** models.
- Evaluate models using accuracy, precision, recall, and confusion matrix.

### **Key Insights:**
1. **Study time** and **parental education** strongly influenced pass rates.
2. Logistic Regression gave better interpretability.
3. Decision Tree captured non-linear patterns but risked overfitting.

---

## **📅 Week 3: Customer Segmentation**
**Goal:** Segment customers based on demographics and spending patterns using **K-Means clustering**.

### **Tasks:**
- Scale features (**Age**, **Annual Income**, **Spending Score**).
- Determine optimal clusters using the **Elbow Method**.
- Visualize customer groups using scatter plots.

### **Key Insights:**
- **Cluster 0:** High income, high spending — most profitable customers.
- **Cluster 1:** Low income, low spending — price-sensitive group.
- **Cluster 2:** High income, low spending — potential to target with premium offers.
- **Cluster 3:** Low income, high spending — impulse buyers.

---

## **📅 Week 4: Loan Approval Prediction System**
**Goal:** Build an end-to-end ML pipeline to predict loan approval.

### **Tasks:**
- Preprocess data (handle nulls, encode categories, remove Loan_ID).
- Train classification model (**Random Forest**).
- Save the model and encoders for deployment.
- Create a **Streamlit** app for real-time predictions.

### **Key Insights:**
1. **Credit history** was the most influential factor in loan approval.
2. Applicants with high income and low loan amount had the highest approval rates.
3. The deployed Streamlit app allowed both **custom inputs** and **quick test cases** for demonstration.

---

## 🚀 **Technologies Used**
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Joblib
- **Deployment:** Streamlit, LocalTunnel
- **Tools:** Kaggle API, Google Colab

---

## 📌 **How to Run**
1. Clone the repository.
2. Upload your `kaggle.json` to Google Colab for dataset downloads.
3. Run the `.ipynb` files for each week’s task.
4. For Week 4:
   - Run `app.py` using Streamlit in Colab.
   - Access the public link provided by LocalTunnel.
