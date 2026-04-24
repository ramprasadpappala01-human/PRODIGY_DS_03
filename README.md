# 🌳 Bank Marketing Prediction using Decision Tree

## 📌 Project Overview

This project builds a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit based on bank marketing data.

The workflow includes:

* Data preprocessing
* Encoding categorical variables
* Model training
* Evaluation using metrics and visualizations

---

## 🎯 Objective

To classify customers into:

* **Yes (1)** → Will subscribe
* **No (0)** → Will not subscribe

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Dataset

* File used: `bank.csv`
* Separator: `;`
* Contains customer details such as:

  * Age
  * Job
  * Marital Status
  * Education
  * Balance
  * Loan status
  * Contact information
  * Campaign details

---

## ⚙️ Data Preprocessing

* Converted categorical columns using **Label Encoding**
* Stored encoders for future reference
* Split dataset into:

  * **Features (X)**
  * **Target (y)**

---

## 🔀 Train-Test Split

* Training set: 70%
* Testing set: 30%
* Stratified sampling to maintain class balance

---

## 🌳 Model Details

* Algorithm: Decision Tree Classifier
* Criterion: Gini Index
* Max Depth: 5
* Random State: 42

---

## 📊 Model Evaluation

### ✅ Accuracy Score

Measures overall correctness of the model.

### 📋 Classification Report

Includes:

* Precision
* Recall
* F1-score

### 🔲 Confusion Matrix

Visualized using a heatmap:

* True Positives
* True Negatives
* False Positives
* False Negatives

---

## 📈 Visualizations

* Confusion Matrix Heatmap
* Decision Tree Diagram (full model visualization)

---

## 🚀 How to Run

### 1. Clone the repository

```bash id="2g9q0x"
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies

```bash id="3l9vha"
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Run the script

```bash id="8nqf4k"
python your_script_name.py
```

---

## ⚠️ Notes

* Ensure `bank.csv` is in the same directory
* Label Encoding is applied to all categorical columns
* Model performance may vary depending on dataset quality

---

## 💡 Future Improvements

* Hyperparameter tuning (GridSearchCV)
* Feature importance analysis
* Try ensemble models (Random Forest, XGBoost)
* Handle class imbalance more effectively

---

## 📬 Contact

Feel free to connect for suggestions or improvements!

---

⭐ If you found this project useful, consider giving it a star!
