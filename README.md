# SVM Optimization on Statlog (Landsat Satellite) Dataset

This project implements Support Vector Machine (SVM) optimization on the Statlog (Landsat Satellite) dataset from the UCI Machine Learning Repository. It is part of an academic assignment focused on hyperparameter tuning and model performance evaluation for multi-class classification problems.

## 📊 Dataset

- **Name:** Statlog (Landsat Satellite)
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Statlog+(Landsat+Satellite))
- **Classes:** 6
- **Instances:** 6435
- **Features:** 36 continuous features

## 🧪 Project Description

- The dataset is divided into 10 different random samples with a 70-30 training-testing split.
- For each sample, the SVM is optimized over **100 iterations** to find the best combination of:
  - **Kernel**
  - **Nu** (used with Nu-SVC)
  - **Epsilon** (used in regression-based SVMs if applicable)
- Best parameters and accuracies are recorded for each sample in a comparative table.
- A convergence graph is plotted for the sample achieving the highest accuracy.

## 📈 Results

- **Table 1:
- ![image](https://github.com/user-attachments/assets/9aeafc24-de48-44b2-bfa8-086b52dda153)

- **Figure 1:
- ![image](https://github.com/user-attachments/assets/ef8b3262-901f-43e6-b06b-0bc64d30a591)


## 🛠️ Technologies Used

- Google Colab (Python runtime)
- Scikit-learn
- NumPy, Pandas
- Matplotlib / Seaborn

## 📎 License

This project is developed for academic purposes as part of a machine learning assignment. All rights reserved by the author.

---
