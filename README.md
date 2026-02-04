# Fake Job Posting Detection using Machine Learning

##  Project Overview
This project detects fraudulent job postings using Natural Language Processing (NLP) and Machine Learning techniques. The model classifies job postings as real or fake based on textual features.

---

##  Problem Statement
Online job portals are often targeted by scammers posting fake job listings. This project aims to automatically identify such fraudulent postings to improve user safety.

---

##  Dataset
- Source: Kaggle – Real or Fake Job Posting Dataset
- Total records: ~17,800
- Target column: `fraudulent`
  - 0 → Real Job
  - 1 → Fake Job

---

##  Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression

---

##  Methodology
1. Data loading and preprocessing
2. Handling missing values
3. Combining text columns
4. Text cleaning
5. TF-IDF vectorization
6. Train-test split
7. Logistic Regression model training
8. Model evaluation

---

##  Data Visualization
- Class distribution of real vs fake job postings
- Confusion matrix visualization
- Evaluation metrics analysis

---

##  Results
- Accuracy: ~97.5%
- High precision for fake jobs
- Lower recall due to class imbalance
- Class-weight balancing used to improve fraud detection

---

##  Future Improvements
- Use advanced NLP models (BERT)
- Apply oversampling techniques
- Deploy as a web application

---

## 📌 Conclusion
This project demonstrates a practical NLP-based fraud detection system using machine learning.
