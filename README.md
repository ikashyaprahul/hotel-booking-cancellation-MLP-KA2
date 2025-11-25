# 🏨 Hotel Booking Cancellation Prediction

[![Kaggle](https://img.shields.io/badge/Kaggle-Competition-blue.svg)](https://www.kaggle.com/competitions/mlp-term-3-2025-kaggle-assignment-2)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains a machine learning project to predict hotel booking cancellations. It was developed for a Kaggle competition as part of the Machine Learning Practice course at IIT Madras.

## 📝 Table of Contents

- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results](#-results)
- [License](#-license)
- [Contact](#-contact)

## 🔑 Key Features

- **Data Preprocessing:** Cleans and preprocesses data by handling missing values and engineering new features from date columns.
- **Exploratory Data Analysis (EDA):** Visualizes key data distributions and correlations.
- **Model Training:** Trains 7 different machine learning models to predict cancellations.
- **Hyperparameter Tuning:** Optimizes the 3 best-performing models for improved accuracy.
- **Automated Model Selection:** Automatically selects the best model, retrains it on the full dataset, and generates a submission file.

## 💻 Technology Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- LightGBM

## 🚀 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ikashyaprahul/hotel-booking-cancellation-MLP-KA2
   cd hotel-booking-cancellation-MLP-KA2
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the dataset:**
   - Download the data from the [Kaggle competition page](https://www.kaggle.com/competitions/mlp-term-3-2025-kaggle-assignment-2).
   - Place `train.csv`, `test.csv`, and `sample_submission.csv` in the `data/` directory.

## ▶️ Usage

1. **Navigate to the notebook directory:**
   ```bash
   cd notebook
   ```

2. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook 23f1003149.ipynb
   ```

3. **Run the cells:**
   - Execute the cells in the notebook to run the machine learning pipeline.
   - The final `submission.csv` will be saved in the `results/` directory.

## 🏆 Results

The project achieves high accuracy in predicting booking cancellations. The best model is selected based on validation set performance, and a `submission.csv` file is generated for the Kaggle competition. For detailed results, refer to the Jupyter Notebook.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 💬 Contact

Kashyap Rahul - [ikashyaprahull@gmail.com ] - [https://www.linkedin.com/in/kashyaprahul2002/]
