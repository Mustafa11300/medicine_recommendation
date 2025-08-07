
# 🧠 Medicine Recommendation System

This is a **Flask-based web application** that predicts the most likely disease based on user-entered symptoms and suggests corresponding **medications, precautions, diets, workouts**, and a **disease description**. It uses a trained Support Vector Classifier (SVC) model and various supporting datasets.

---

## 📂 Project Structure

```

Medicine\_Recom/
│
├── **pycache**/
├── datasets/
│   ├── symptoms\_df.csv
│   ├── precautions\_df.csv
│   ├── workout\_df.csv
│   ├── description.csv
│   ├── medications.csv
│   └── diets.csv
│
├── models/
│   └── svc.pkl
│
├── templates/
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   ├── developer.html
│   └── blog.html
│
├── main.py
└── README.md

````

---

## 🚀 Features

- Input multiple symptoms manually.
- Predict disease based on symptoms using ML model.
- Recommends:
  - Description of disease
  - Precautions
  - Medications
  - Diet plans
  - Suggested workouts
- Web UI built using HTML templates and Flask backend.

---

## 🧪 How It Works

1. The model is trained to map input symptoms to a disease using the `svc.pkl` classifier.
2. User inputs symptoms through the web interface (comma-separated).
3. The model processes the input, predicts the disease, and fetches all relevant recommendations from the datasets.

---

## 💻 Getting Started

### 🔧 Prerequisites

- Python 3.x
- Flask
- NumPy
- Pandas
- scikit-learn
- Pickle

### 📦 Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/medicine_recommendation.git
cd medicine_recommendation/Medicine_Recom
````

2. Install dependencies:

```bash
pip install -r requirements.txt
```

> If `requirements.txt` is missing, install manually:

```bash
pip install flask numpy pandas scikit-learn
```

---

## 🏃 Running the Application Locally

```bash
python main.py
```

Then open your browser and go to:
👉 `http://127.0.0.1:5000`

---

## 🌐 Pages

* `/` → Home (input symptoms & get prediction)
* `/about` → About the system
* `/contact` → Contact page
* `/developer` → Developer information
* `/blog` → Placeholder for blog content

---

## 📊 Model Used

* **Classifier:** Support Vector Classifier (`svc.pkl`)
* **Features:** Binary presence/absence of 132 symptoms
* **Output:** 41 unique diseases

---

## ⚠️ Limitations

* Only works with symptoms available in the `symptoms_dict`
* Model accuracy may vary depending on training data
* This is not intended for real-world medical use

---

## 🙋‍♂️ Author

**Mustafa11300**
GitHub: [@Mustafa11300](https://github.com/Mustafa11300)

---

## 📝 License

This project is for educational purposes only and is not licensed for clinical or commercial use.

```

---

Let me know if you want me to generate this as a `.md` file you can download.
```
