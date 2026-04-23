# 🏠 House Price Predictor

![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)
![scikit-learn](https://img.shields.io/badge/ML-scikit--learn-orange?logo=scikitlearn)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)

A beginner-friendly machine learning web app that predicts the **median house value** in California using a trained model and an interactive **Streamlit** UI.

---

# 📊 Dataset

* **Source:** California Housing Dataset (`housing.csv`)

---

# 🤖 Model

* **Algorithm:** Random Forest Regressor
* **Training Sample:** 5,000 random samples from the dataset

### 🔧 Preprocessing:

* Missing value handling
* One-hot encoding for categorical column (`ocean_proximity`)
* Feature scaling not required for tree-based models

---

# 🛠️ Tools & Libraries

* Python 3.13 🐍
* pandas
* scikit-learn
* joblib
* streamlit

---

# 🚀 How to Run

### 1️⃣ Clone this repository

```bash
git clone https://github.com/Aditya13136/House-Price-Predictor/tree/master/House-Price-Predictor-main
cd house-price-predictor
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
pip install pandas scikit-learn joblib streamlit
```

### 3️⃣ Train and save model

```bash
python model.py
```

### 4️⃣ Run the Streamlit app

```bash
streamlit run app.py
```

---

# 🎬 Demo

![Demo]

---

# 📝 Notes

* The model is saved as `saved_model/model.pkl`
* You can experiment with other regressors like:

  * Gradient Boosting
  * XGBoost
* Input is taken via Streamlit sliders for a smooth user experience 🎯

---

# 📁 Folder Structure

```
house-price-predictor/
│
├── data/
│   └── housing.csv
│
├── saved_model/
│   └── model.pkl
│
├── app.py
├── model.py
├── README.md
└── .gitignore
```
