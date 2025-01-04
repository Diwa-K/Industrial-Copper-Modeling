# Copper Industry: Sales and Lead Prediction using Machine Learning

## **Project Overview**
The copper industry faces challenges in accurate sales and pricing predictions due to skewed and noisy data, as well as inefficiencies in lead classification. This project utilizes machine learning techniques to address these issues. It builds two models: a regression model to predict `Selling_Price` and a classification model to predict lead `Status` (WON/LOST). The project is integrated with a Streamlit web application for user-friendly interaction.

---

### Objectives:
1. Explore skewness and outliers in the dataset.
2. Perform data cleaning, transformation, and preprocessing.
3. Build a regression model to predict `Selling_Price`.
4. Create a classification model to predict lead `Status` (WON/LOST).
5. Develop a Streamlit web application to make predictions interactively.

---

## **Technologies Used**
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Streamlit

---

## **Learning Outcomes**
1. Develop proficiency in Python and data analysis libraries.
2. Gain expertise in data preprocessing techniques:
   - Handling missing values
   - Outlier detection
   - Data normalization
3. Perform exploratory data analysis (EDA) using visualizations (boxplots, histograms, scatter plots).
4. Apply regression and classification techniques for predictive modeling.
5. Optimize models using cross-validation and grid search.
6. Implement feature engineering for improved model performance.
7. Create a Streamlit-based interactive web application for predictions.
8. Understand challenges and best practices in the manufacturing domain.

---

## **Project Workflow**

### **Step 1: Data Exploration and Preprocessing**
- Load and explore the dataset.
- Handle skewness and outliers using appropriate transformations.
- Clean and preprocess the data (e.g., missing value handling, feature scaling).

### **Step 2: Exploratory Data Analysis (EDA)**
- Visualize data distributions and relationships using boxplots, histograms, and scatter plots.
- Identify key trends and insights.

### **Step 3: Regression Model**
- Target Variable: `Selling_Price`
- Build a regression model to predict continuous target variables.
- Algorithms: Linear Regression, Random Forest, or Gradient Boosting.

### **Step 4: Classification Model**
- Target Variable: `Status` (WON/LOST)
- Focus on binary classification to evaluate lead success probability.
- Algorithms: Logistic Regression, Decision Tree, or Random Forest.

### **Step 5: Model Evaluation and Optimization**
- Use evaluation metrics such as R², Mean Squared Error (MSE) for regression.
- Use metrics such as accuracy, precision, recall, and F1-score for classification.
- Optimize models using techniques like cross-validation and grid search.

### **Step 6: Streamlit Application Development**
- Create an interactive user interface to input column values.
- Display predicted results for:
  - Selling Price (Regression Model)
  - Status: WON/LOST (Classification Model)

---

## **Future Scope**
1. Extend models to predict additional variables or statuses.
2. Incorporate real-time data for dynamic predictions.
3. Enhance the Streamlit app with advanced visualization techniques.

---



