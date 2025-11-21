# Tumor Detection Project 🏥
# data science Assignment -7
## 📌 Overview
This project uses Machine Learning to classify breast cancer tumors as either **Malignant (M)** or **Benign (B)** based on various features like radius, texture, and perimeter.

## 🛠️ Technologies Used
* **Language:** Python
* **Libraries:** Pandas, Seaborn, Matplotlib, Scikit-learn
* **Model:** Random Forest Classifier

## 📊 Workflow
1. **Data Loading:** Loaded the `Tumor_Detection.csv` dataset.
2. **Data Cleaning:** Removed unnecessary columns (`id`, `Unnamed: 32`).
3. **EDA:** Visualized diagnosis counts and feature correlations using heatmaps.
4. **Preprocessing:** Mapped 'M'/'B' to 1/0, split data (80/20), and applied **Standard Scaling**.
5. **Modeling:** Trained a **Random Forest Classifier**.

## 📈 Results
* The model achieved high accuracy in classifying tumor types.
* Key features for detection were identified through correlation analysis.
