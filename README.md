
# 🧠 Disease Prediction & Medicine Recommendation System

A local Flask web application that predicts the most likely disease based on user-entered symptoms and recommends medications, precautions, and a description using a trained Support Vector Classifier (SVC) model.

---

## 🚀 Features

- Input multiple symptoms (comma-separated)
- Predict disease using a trained ML model
- Get recommended:
  - ✔️ Description
  - 💊 Medications
  - 🛡️ Precautions

---

## 🏗️ Tech Stack

- **Frontend**: HTML, CSS, Jinja2 Templates
- **Backend**: Python (Flask)
- **Machine Learning**: Scikit-learn (SVC Model)
- **Datasets**: CSV files (symptoms, medications, descriptions, precautions)

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/medicine-recom.git
cd medicine-recom
````

### 2. Create & Activate a Virtual Environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows
```

### 3. Install Required Packages

```bash
pip install flask pandas scikit-learn numpy
```

### 4. Run the App Locally

```bash
python main.py
```

Then open your browser and navigate to:
👉 `http://127.0.0.1:5000`

---

## 💡 How to Use

1. Open the local web app in your browser.

2. Enter symptoms (comma-separated), e.g.:

   ```
   headache, nausea, vomiting
   ```

3. Click **Predict**.

4. View the predicted disease and its:

   * Description
   * Medications
   * Precautions

---

## 🧠 ML Model

* **Model Type**: Support Vector Classifier (SVC)
* **Trained On**: Binary matrix of 132 symptoms
* **Prediction Output**: One of 41 diseases

---

## ⚠️ Limitations

* Only accepts symptoms that are pre-defined in the `symptoms_dict`
* Predictions are based on model accuracy and input quality
* **⚕️ Not intended for real medical use**

---
