# 🌱 Fertilizer Recommendation System – Week 2  

## 📌 Objective  
The goal of Week 2 was to **train machine learning models** using the preprocessed dataset (from Week 1) and evaluate their performance in predicting the correct fertilizer recommendation.  

---

## ⚙️ Steps Completed  

### 1. Data Preprocessing  
- Used **Label Encoding** for target variable (`Fertilizer Name`).  
- Applied **One-Hot Encoding** to categorical features (`Soil Type`, `Crop Type`).  
- Split the dataset into **Training (80%)** and **Testing (20%)** sets.  

---

### 2. Model Training  
Trained and tested multiple ML models:  
- 🌳 Decision Tree  
- 🤝 K-Nearest Neighbors (KNN)  
- 📈 Logistic Regression  
- 🌲 Random Forest  

---

### 3. Model Evaluation  
- Compared performance of all models.  
- Evaluated accuracy and generated **classification reports**.  
- Selected the **best model** automatically based on accuracy.  

---

## 📊 Results  

| Model               | Accuracy |
|----------------------|----------|
| Decision Tree        | ~0.145   |
| KNN                  | ~0.145   |
| Logistic Regression  | ~0.140   |
| Random Forest        | ~0.147   |

- The **best performing model** was **Random Forest**, but accuracy remained low (~15%).  
- This shows the dataset is **challenging / noisy**, and further tuning or domain knowledge (rule-based methods) may be required.  

---

## 🌱 Sample Prediction  

Example prediction on a new input:  
```bash
🌱 Predicted Fertilizer Recommendation: Urea
```

---

## 📂 Files in Week 2  
- `Week2_Fertilizer_Recommendation.ipynb` → Jupyter Notebook with full Week 2 implementation.  
- `Fertilizer Prediction.csv` → Dataset file (used from Week 1).  
- `README.md` → This documentation file.  

---

## 🚀 Next Steps (Week 3 Plan)  
- Perform **hyperparameter tuning** (GridSearchCV).  
- Handle possible **class imbalance**.  
- Explore **rule-based + ML hybrid system** to improve recommendation accuracy.  
