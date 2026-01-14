# Mobile Price Range Prediction – Machine Learning Project

## Project Overview
This project focuses on predicting the **price range of mobile phones** using machine learning techniques.  
The main objective is to **compare the performance of five different classification models** and select the best-performing model based on multiple evaluation metrics.

---

## Objective
- To analyze mobile phone specifications
- To build and compare multiple machine learning models
- To identify the **best model** for predicting mobile price ranges (0, 1, 2, 3)

---

## Dataset
The dataset contains various mobile phone features such as:
- Battery_power        ​
- blue ​
- clock_speed ​
- dual_sim ​
- fc ​
- four_g ​
- int_memory ​
- m_dep ​
- mobile_wt ​
- n_cores ​
- pc ​
- px_height ​
- px_width ​
- ram ​
- sc_h ​
- sc_w ​
- talk_time ​
- three_g ​
- touch_screen ​
- Wifi ​
- price_range (target) ​

​
​ 

Target variable:
- **price_range** (0 = Low, 1 = Medium, 2 = High, 3 = Very High)

---

## Project Workflow
1. Data Loading and Checking  
2. Data Cleaning (handling missing values and duplicates)  
3. Feature Unit Verification and Conversion  
4. Exploratory Data Analysis (EDA)  
   - Target distribution  
   - Correlation heatmap  
   - Box plots  
   - Feature distribution (Histogram + KDE)  
5. Feature Engineering  
6. Train–Test Split (80/20)  
7. Feature Scaling (Standardization)  
8. Model Training (5 models)  
9. Hyperparameter Tuning (GridSearchCV)  
10. Cross-Validation Comparison  
11. Final Test Evaluation  
12. Feature Importance Analysis  
13. Visualization and Interpretation  

---

## Machine Learning Models Used
- SGD Linear Classifier  
- Logistic Regression  
- Decision Tree (Entropy / ID3-style)  
- Random Forest  
- K-Nearest Neighbors (KNN)  

---

## Model Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  
- Classification Report  

---

## Best Model
**Logistic Regression** was selected as the best model because:
- Highest test accuracy (97.5%)
- Lowest error rate
- Balanced precision, recall, and F1-score
- Consistent performance across all price ranges
- Good generalization in cross-validation

---

## Files in This Repository
- `ml_project.ipynb` → Complete Google Colab notebook with code and outputs  
- `presentation.pptx` → Project presentation slides  
- `project_report.pdf` → Detailed project report  

---

## Tools and Libraries
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## Usage Restriction
This repository is publicly visible **for academic review purposes only**.  
Copying, reusing, modifying, or redistributing any part of this code **without explicit permission from the author is strictly prohibited**.

---

## Author
Yash Thakur
