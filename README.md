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
 1. Data collection​
 2. Preprocessing​
      - DATA CHECKING​
      - DATA CLEANING​
      - VERIFY FEATURE UNIT​
      - UNIT CONVERSION​
      - EDA​
      - FEATURE ENGINEERING​
      - ENCODING TARGET​
      - TRAIN/TEST SPLIT ​
      - SCALING​
4. Train model​
5. Hyperparameter tuning​
6. Evaluate and compare​
   - CROSS VALIDATION​
   - FINALE TEST EVALUATION​
     - Confusion matrix of all 5 model with classification report​
     - Visual representation of confusion matrix​
     - Classification report for best model​
     - Test accuracy​
   - FEATURE IMPORTANCE​
   - SCATTER PLOT FOR EVERY MODEl​

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
- Logistic Regression​ Justification:​
- Logistic Regression was selected as the best model because:​
1. It achieved the highest test accuracy (97.5%)​
2. It had the lowest error percentage (2.5%)​
3. It showed consistent performance across all classes​
4. Precision, recall, and F1-score were uniformly high​
5. The confusion matrix showed minimal misclassification​
6. The model generalized well during cross-validation​
7. It is computationally efficient and easy to interpret​

---

## Files in This Repository
- `ml_project.ipynb` → Complete Google Colab notebook with code and outputs  
- `presentation.pptx` → Project presentation slides  
- `project_report.docx` → Detailed project report
- `mobile_price_range_data.csv` → Dataset  

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
Yash Pratap Singh Thakur
