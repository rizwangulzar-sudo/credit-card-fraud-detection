# 💳 Credit Card Fraud Detection using Machine Learning

This project uses the **Kaggle Credit Card Fraud Detection dataset** to build a machine learning pipeline that identifies fraudulent transactions. The goal is to explore both **unsupervised anomaly detection** and **supervised classification** methods on a highly imbalanced dataset.

## 📁 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Description: Contains transactions made by European cardholders in September 2013.
- Total transactions: 284,807
- Fraudulent transactions: 492 (0.17%)

⚠️ Due to GitHub file size limits, the full dataset is not uploaded here. Please download it directly from Kaggle and place it in the root folder as `creditcard.csv`.

---

## 🔍 Project Workflow

### 1. 📊 Data Processing & EDA
- Loaded and explored the dataset
- Checked class imbalance and missing values
- Visualized transaction distributions

### 2. ⚠️ Unsupervised Anomaly Detection
- Isolation Forest
- One-Class SVM

### 3. ✅ Supervised Learning
- Logistic Regression
- Random Forest
- XGBoost

### 4. 🧪 Evaluation Metrics
- Confusion Matrix
- Precision, Recall, F1-Score
- ROC-AUC

### 5. 📈 Visualization
- Correlation heatmaps
- PCA for dimensionality reduction
- Model performance plots

---

## 🛠️ Tools & Libraries

- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Google Colab

---

## 🚀 How to Run

1. Clone the repo or open the notebook in Google Colab
2. Download the dataset from Kaggle
3. Upload `creditcard.csv` in the working directory
4. Run all cells to see results

---

## 🙋‍♂️ Author

This project is part of my ongoing journey in learning data science and machine learning.  
I’m currently exploring real-world applications such as fraud detection, anomaly detection, and AI automation.

Connect with me on [LinkedIn]([https://linkedin.com/](https://www.linkedin.com/in/muhammad-rizwan-gulzar-9b802b117/)) or explore more on my GitHub.

---

## 📌 License

This project is licensed under the MIT License. You are free to use, modify, and share it with proper attribution.
