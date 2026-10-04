# Random Forest Project

## Overview
This project demonstrates the implementation of a **Random Forest Classifier** for binary classification tasks.  
It also compares performance with a **Decision Tree Classifier** using metrics such as accuracy, precision, recall, F1‑score, and confusion matrix.

---

## Dataset
- Contains loan application features and target labels (0 = non‑default, 1 = default).  
- Preprocessing includes handling categorical variables with `pd.get_dummies()` and splitting into train/test sets.

---

## Models Implemented
- Decision Tree Classifier  
- Random Forest Classifier  

---

## Evaluation Metrics
- Accuracy  
- Precision, Recall, F1‑score  
- Confusion Matrix  

### Example Results
- **Decision Tree**: Accuracy ~73%, better recall for minority class.  
- **Random Forest**: Accuracy ~85%, stronger majority class performance but weaker minority class recall.  

---
