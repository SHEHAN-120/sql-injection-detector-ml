# 🛡️ SQL Injection Detector using Machine Learning

This project is a simple machine learning-based system that detects SQL injection attempts from text queries. It uses a Random Forest Classifier trained on labeled query data and employs a TF-IDF vectorizer for text feature extraction.

## 📌 Features

* Detects SQL Injection attempts in query strings.
* Trained using TF-IDF and Random Forest Classifier.
* Easy-to-use prediction function.
* Model and vectorizer saved as `.pkl` files for deployment.

## 💡 Use Case

This can be integrated into web applications or security pipelines to pre-scan incoming queries and flag potentially malicious SQL injection attacks.

## 🚀 Demo

```python
print(sql_detect("or 1--"))
# Output: SQL Injection Detected
```

## 🧰 Tools & Technologies

* Python
* Scikit-learn (`sklearn`)
* Pandas
* NumPy
* TfidfVectorizer
* RandomForestClassifier
* Pickle (for model serialization)
* Excel dataset (query vs. label)

## 🧠 Skills Applied

* Machine Learning (Supervised Classification)
* Feature Extraction using TF-IDF
* Model Evaluation and Accuracy Testing
* File Handling and Model Deployment



## 📈 Model Info

* **Classifier**: RandomForestClassifier
* **Vectorizer**: TfidfVectorizer
* **Test Accuracy**: Based on dataset 

## 🏁 Getting Started

### Installation

### Run Training & Save Model

### Prediction Function

```python
sql_detect("SELECT * FROM users WHERE id = 1")
```

## 🗜️ License

This project is open-source and available under the [MIT License](LICENSE).

---

**Made with ❤️ by Shehan**
