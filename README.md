# BRAIN_WAVE_MATRIX_SOLUTION
Data Science/ Data Analytics

**🎯 Task 1**

# 🛒 Supermarket Sales Data Analysis

## 📌 Project Overview  
An end-to-end **data preprocessing** and **exploratory data analysis (EDA)** of a commercial supermarket dataset using **Python** and **Jupyter Notebook**.

---

## 📌 Objective

To perform an in-depth **sales analysis** of a supermarket business using a structured approach that includes:
- Data cleaning
- Feature engineering
- Descriptive statistics
- Visual exploration

---

## 📊 Dataset

- **Name:** Supermarket Sales Dataset  
- **Source:** Public (CSV format)  
- **Features:** `Invoice ID`, `Branch`, `City`, `Customer Type`, `Gender`, `Product Line`, `Total`, `Date`, `Time`, `Payment`, etc.

---

## 🔧 Tools & Libraries Used

- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- WordCloud  

---

## 📈 Analysis Covered

### 1. **Data Preprocessing**
- Converted `Date` and `Time` columns to datetime format
- Extracted `day`, `month`, `year`, and `hour` for time-based analysis
- Handled missing or malformed data

### 2. **Descriptive Analysis**
- Correlation matrix
- Relationship between `Tax`, `Total`, `Gross Income`, and `Cogs`
- Calculated and visualized average customer rating

### 3. **Custom Visual Functions**
- Created reusable functions for:
  - `countplot`
  - `boxplot`
  - `lineplot`
  - `relplot`

### 4. **Key Business Questions Answered**
- Which **city** or **branch** generates the most revenue?
- What **time of day** sees the most sales?
- What are the **customer preferences** by product line and branch?
- Does **customer type** affect rating and sales?
- What are the preferred **payment methods**?
- What are the most **popular product categories**? *(via WordCloud)*

---

## 📌 Visual Insights

- 📉 Sales trends by **hour**, **month**, and **branch**
- 📦 Product line distribution across branches
- 💳 Customer payment preferences
- 🛍️ Product popularity using **WordCloud**

---

## 💡 Conclusion

This project demonstrates a complete workflow for commercial sales analysis:
- ✅ Preprocessing raw data  
- ✅ Creating new time-based features  
- ✅ Identifying key business patterns  
- ✅ Visualizing insights using Python  

---
---

**🎯 Task 2**
# 🧠 Social Media Sentiment Analysis  

## 📌 Project Overview  
This project aims to analyze public sentiment on Twitter using **Natural Language Processing (NLP)**. The objective is to determine whether a tweet expresses a **positive** or **negative** sentiment using machine learning techniques.

---

## 📁 Dataset  
**Name**: Sentiment140  
**Source**: [Kaggle - Sentiment140 Dataset] 
**Description**: Contains 1.6 million labeled tweets with sentiment (0 = negative, 4 = positive).

---

## 🛠️ Technologies & Tools
- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- NLTK (for stopwords & stemming)  
- Scikit-learn (for model building & evaluation)  
- Logistic Regression  
- TF-IDF Vectorizer  
- Pickle (for model saving)

---

## ⚙️ Steps Performed
1. **Data Preprocessing**  
   - Removed unwanted characters  
   - Converted text to lowercase  
   - Removed stopwords  
   - Performed stemming  

2. **Feature Extraction**  
   - TF-IDF vectorization to convert text into numerical features  

3. **Model Building**  
   - Trained a Logistic Regression model  
   - Accuracy on test data: **~77.8%**

4. **Model Evaluation**  
   - Accuracy Score  
   - Classification Report  
   - Confusion Matrix  
   - Sample Predictions

5. **Model Deployment (Optional)**  
   - Pickle used to save and load the trained model

---

## 📊 Visualizations
- Bar charts for sentiment distribution  
- WordCloud (optional)  
- Accuracy & confusion matrix plots
  
---


