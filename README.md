# 🏦 Customer Transaction Prediction

This project predicts whether a customer will make a future transaction based on anonymized banking data. It leverages machine learning models to help financial institutions identify potential customers for personalized offers, marketing, and retention strategies.

---

## 📌 Project Overview

* Performed **data cleaning, preprocessing, and exploratory data analysis (EDA)**.
* Built and evaluated **machine learning models** (Logistic Regression, Random Forest, XGBoost, LightGBM).
* Achieved high **ROC-AUC score** and strong classification metrics.

---

## 📂 Dataset

The dataset is anonymized to protect privacy.
Due to GitHub’s file size restrictions, datasets are **not included** in this repository.

🔗 **Download Dataset Here:**


* [Dataset Link]([https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1003-CustTransPred.zip](https://drive.usercontent.google.com/download?id=1l0eT-fCvxDZNJ7cTY6t5s4GbFr5MHZUr&authuser=0))



---

## ⚙️ Tech Stack

* **Language**: Python 3.x
* **Libraries**:

  * `pandas`, `numpy` → Data preprocessing
  * `matplotlib`, `seaborn` → Data visualization
  * `scikit-learn` → Model training and evaluation
  * `xgboost`, `lightgbm` → Gradient boosting models

---

## 🚀 Project Workflow

1. **Data Preprocessing**

   * Handling missing values
   * Feature encoding & scaling
   * Train-test split

2. **Exploratory Data Analysis (EDA)**

   * Feature distributions
   * Correlation heatmaps
   * Class imbalance checks

3. **Model Building**

   * Logistic Regression
   * Random Forest
   * Gradient Boosting (XGBoost, LightGBM)

4. **Evaluation Metrics**

   * Accuracy
   * Precision, Recall, F1-score
   * ROC-AUC

---

## 📊 Results

* Gradient Boosting models performed best.
* Strong **ROC-AUC** and balanced **precision/recall**, making the model reliable for transaction prediction.

---

## 📜 Future Improvements

* Hyperparameter tuning for further accuracy.
* Model deployment via Flask/Django API.
* Real-time prediction system integration.

---

## 🗂️ Project Structure

```
Customer-Transaction-Prediction/
│── Data/                # Place dataset here (not included in repo)
│── notebooks/           # Jupyter notebooks for EDA & modeling
│── models/              # Saved ML models
│── src/                 # Source code (data prep, training scripts)
│── requirements.txt     # Dependencies
│── README.md            # Project documentation
```

---

## 📥 Installation & Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/pamd005/Customer-Transaction-Prediction.git
   cd Customer-Transaction-Prediction
   ```

2. Create virtual environment & install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Place dataset inside `Data/` folder.

4. Run Jupyter Notebook or Python scripts for training:

   ```bash
   jupyter notebook
   ```

---

## 📜 License

This project is licensed under the **MIT License**.
