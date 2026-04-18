# Machine Learning Internship Project  

<p align="center">
  <b>End-to-End Machine Learning Pipeline | Regression • Classification • Advanced Models</b>
</p>

---

## Overview  
This repository showcases my internship work where I implemented machine learning models across multiple levels — from **basic regression** to **advanced ensemble and SVM models**.

The project demonstrates a **complete ML workflow**:
> Data Preprocessing → Model Building → Evaluation → Visualization → Insights

---

## Key Highlights  

Implemented **3 Levels of Machine Learning Tasks**  
Built **Regression + Classification + Advanced Models**  
Visualized results using graphs and confusion matrices  
Performed **feature importance analysis**  
Compared multiple models for performance  

---

## Repository Structure  
ML-Internship-Project/
│
├── Level1_HousePrice_Regression.ipynb
├── Churn_Prediction_Level2_Level3.ipynb
│
├── churn-bigml-80.csv (Training Data)
├── churn-bigml-20.csv (Testing Data)


---

## Level 1: House Price Prediction  

**Goal:** Predict house prices using regression  

### Workflow  
- Data preprocessing  
- Feature scaling  
- Linear Regression model  

### Evaluation  
- R² Score  
- Mean Squared Error  

---

## Level 2: Customer Churn Prediction  

**Goal:** Predict whether a customer will churn  

### Models Used  
- Logistic Regression  
- Decision Tree  

### Evaluation  
- Accuracy Score  
- Confusion Matrix  
- Classification Report  

---

## Level 3: Advanced Machine Learning  

**Goal:** Improve model performance using advanced techniques  

### Models Used  
- Random Forest  
- Support Vector Machine (SVM)  

### Advanced Analysis  
- Feature Importance (Random Forest)  
- Model Comparison  
- Kernel comparison (Linear vs RBF)  

---

##Results & Insights  

Decision Tree achieved the highest accuracy  
Random Forest performed strongly with balanced predictions  
Logistic Regression provided a solid baseline  
SVM (Linear) struggled with class imbalance  
SVM (RBF) improved performance significantly  

### Model Performance Comparison  

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 0.853    |
| Decision Tree       | 0.954    |
| Random Forest       | 0.945    |
| SVM (Linear)        | 0.858    |
| SVM (RBF)           | 0.919    |

*Note: Accuracy alone is not sufficient due to class imbalance, so confusion matrix and recall were also analyzed.*

##Tech Stack  

- Python  
- pandas  
- scikit-learn  
- matplotlib & seaborn  

---
## How to Run  

```bash
git clone https://github.com/anukta-acharya/ML-Internship-Project.git
cd ML-Internship-Project
```
Open notebooks in Jupyter / Colab and run cells sequentially

##Conclusion

This project demonstrates a complete machine learning pipeline from basic regression to advanced classification models, focusing on performance, interpretability, and real-world insights.
