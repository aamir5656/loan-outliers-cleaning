# 📊 Outlier Detection in Loan Dataset

In this project, I worked on identifying and removing outliers from a loan dataset using two statistical techniques: **Z‑score** and **IQR method**.  
The goal was to clean the data and make it more reliable for analysis.

---

## 📁 Files Included

| File Name | Description |
|-----------|-------------|
| [Outlier_Loan_dataset.csv](./Outlier_Loan_dataset.csv) | Original raw data with possible outliers |
| [Final_Outliers_clean_dataset.csv](./Final_Outliers_clean_dataset.csv) | Cleaned dataset after outlier removal |
| [Analysis.ipynb](./Analysis.ipynb) | Jupyter Notebook with complete code and explanation |

---

## 🧪 Techniques Used

### 1. Z‑Score Method
- Calculates how far a data point is from the mean in terms of standard deviation.  
- Values with a Z‑score greater than a threshold (commonly 3) are considered outliers.

### 2. IQR (Interquartile Range) Method
- Based on the spread of the middle 50 % of the data.  
- Any point below **Q1 − 1.5 × IQR** or above **Q3 + 1.5 × IQR** is treated as an outlier.

---

## 🔧 How to Run

1. Download or clone this repository.  
2. Open `Analysis.ipynb` in Jupyter Notebook or Google Colab.  
3. Walk through each step to see how outliers are detected and removed.  
4. Final cleaned data will be saved as `Final_Outliers_clean_dataset.csv`.

---

## ✅ Output

- Outliers successfully removed using Z‑score and IQR.  
- Clean dataset is now ready for further statistical analysis or machine‑learning tasks.

---
---

## ▶️ Run on Kaggle

You can also run the full notebook on Kaggle without downloading anything:  
🔗 [Click here to open on Kaggle](https://www.kaggle.com/aamir5659/outlier-detection-and-removal-dataset)

---


Thanks for checking out this work! Suggestions are welcome.
