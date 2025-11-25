# 🏨 Hotel Booking Cancellation Prediction

**IIT Madras – Machine Learning Practice (Kaggle Assignment 2)**
**Author: Kashyap Rahul**

---

## 📌 Overview

This project predicts whether a hotel booking will be **cancelled or not**.
It was completed as part of **Kaggle Assignment 2** for the *Machine Learning Practice* course at IIT Madras.

The goal is to build a complete machine learning pipeline that includes:

* Data cleaning
* Feature engineering
* EDA & visualizations
* Categorical encoding
* Model training (7 models)
* Hyperparameter tuning (3 models)
* Choosing the best model
* Generating a valid Kaggle submission

---

## 📁 Repository Structure

```
├── README.md
├── notebook/
│   └── KA2_notebook.ipynb        # main notebook (your code)
├── results/
│   ├── plots/                    # saved EDA plots
│   └── submission.csv            # final Kaggle submission
├── data/                         # (empty - Kaggle data not uploaded)
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## 🧠 What’s Inside the Notebook

### ✔ Data preprocessing

* Handling missing values
* Converting and extracting date features
* Creating new features like `total_days`, `total_people`, `price_per_person`
* One-hot encoding categorical columns

### ✔ Exploratory Data Analysis

* Booking status distribution
* Price distribution
* Correlation heatmap

### ✔ Model Building (7 Models)

* Logistic Regression
* Random Forest
* Gradient Boosting
* AdaBoost
* KNN
* XGBoost
* LightGBM

### ✔ Hyperparameter Tuning (3 Models)

* Random Forest
* XGBoost
* LightGBM

### ✔ Final Model

The best-performing model is selected automatically, retrained on the full dataset, and used to generate `submission.csv`.

---

## ▶ Running the Notebook

Install dependencies:

```bash
pip install -r requirements.txt
```

Add the Kaggle dataset manually to the `data/` folder:

```
train.csv
test.csv
sample_submission.csv
```

Then open the notebook:

```bash
jupyter notebook notebook/KA2_notebook.ipynb
```

---

## 📄 License

Released under the **MIT License**.

---

## 💬 Contact

If you’d like to connect or discuss improvements, feel free to reach out!

--
