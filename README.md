# 💳 Credit Card Fraud Detection using R



## 📘 Project Overview
This project focuses on detecting fraudulent credit card transactions using **machine learning models in R**.  
It applies and compares the performance of **Decision Tree** and **Random Forest** algorithms to identify whether a transaction is fraudulent or legitimate.  

The model is trained, validated, and evaluated using standard metrics such as **Accuracy**, **Precision**, **Recall**, **F1-Score**, and **AUC**.

---

## 🎯 Objectives
- Build and compare predictive models to detect fraudulent transactions.  
- Analyze transaction patterns and identify features influencing fraud detection.  
- Evaluate models using performance metrics and ROC curves.  

---

## 🧩 Project Workflow
1. **Data Loading and Exploration**  
   - Import transaction dataset and examine structure, summary, and missing values.  
   - Convert date fields and clean unnecessary columns.  

2. **Data Preprocessing**  
   - Encode target variable as categorical (`is_fraud`).  
   - Handle missing values and perform data partitioning into training and testing sets (70–30 split).  

3. **Model Development**  
   - Train **Decision Tree** and **Random Forest** classifiers on training data.  
   - Evaluate both models on the test data.  

4. **Model Evaluation**  
   - Generate confusion matrices for both models.  
   - Calculate performance metrics: Precision, Recall, F1-score, and Accuracy.  
   - Plot and compare ROC curves and compute AUC values.  

---

## 🧠 Tools & Libraries
- **Programming Language:** R  
- **Libraries Used:**  
  - `dplyr` – Data manipulation  
  - `caret` – Model training and evaluation  
  - `rpart` – Decision Tree  
  - `randomForest` – Random Forest Classifier  
  - `e1071` – Statistical modeling and cross-validation  
  - `pROC` – ROC and AUC computation  
  - `readr`, `readxl` – Data import  

---

## 📊 Performance Summary
| Model | Accuracy | AUC | Remarks |
|--------|-----------|-----|----------|
| Decision Tree | ~93% | ~0.95 | Performs well but slightly less stable |
| Random Forest | ~97% | ~0.98 | More robust and accurate model |

---

## 📈 Evaluation Metrics
The models were evaluated using the following metrics derived from the confusion matrix:
- **Precision:** Measures the proportion of correctly predicted frauds out of all predicted frauds.  
- **Recall (Sensitivity):** Measures how many actual frauds were correctly identified.  
- **F1-Score:** Harmonic mean of Precision and Recall for balanced performance.  
- **AUC:** Area under the ROC curve, representing model discrimination ability.  

---

## 🔍 Key Insights
- Random Forest outperformed Decision Tree in both accuracy and AUC.  
- Feature selection and data cleaning play a vital role in improving fraud detection accuracy.  
- ROC curve visualization effectively highlights the classification threshold performance.  

---

## 🏁 Conclusion
The project demonstrates how supervised learning techniques can be effectively applied to detect fraudulent credit card transactions.  
The **Random Forest model** achieved the best performance, showing strong potential for deployment in real-world fraud detection systems.

---

## 👨‍💻 Author
**Aditya Kumar Roy**  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/aditya-kumar-roy-257a1428a/)
