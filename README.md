### 📌 **Title**
**Heart Disease Prediction System using Machine Learning**

---

### 🧠 **Abstract**
- Heart disease is common and treatment can be costly.
- The aim is to predict the disease early using ML and data mining.
- Early prediction improves treatment and reduces cost.
- The system uses ML techniques like Naive Bayes and Decision Trees.
- Predicts based on profile parameters: blood pressure, age, sex, cholesterol, blood sugar.
- Evaluation through confusion matrix, accuracy, precision, and recall.

---

### 📖 **Introduction**
- Healthcare collects vast data often unused.
- Heart Disease Prediction System (HDPS) uses 13 parameters.
- Uses ML algorithms: Naive Bayes, Decision Tree, and Multilayer Perceptron.
- Establishes patterns in medical data for predictions.

---

### 🎯 **Aim**
- Predict heart disease based on user input and database values.

---

### 🎯 **Objective**
- Develop a system that extracts hidden knowledge from historical heart disease data using data mining.

---

### 🌐 **Project Scope**
- Generic software for any organization.
- Summarizes large data efficiently for decision-making.

---

### 🧩 **Modules**
- **Patient Login/Registration**
- **My Details / Disease Prediction**
- **Search Doctor / Feedback**
- **Doctor Login / Patient Details**
- **Admin Login**
  - Add/View Doctor
  - Add/View Dataset
  - View Disease / View Patient
  - View Feedback
  - Notifications for predictions

---

### 💻 **Technology Stack**

#### 👨‍💻 Languages:
- HTML, CSS, JavaScript, Python

#### ⚙️ Frameworks:
- Bootstrap, Django

#### 🤖 Machine Learning Algorithms:
- Gradient Boosting
- Logistic Regression

#### 📦 Libraries:
- NumPy, Pandas, Scikit-learn

#### 🗃️ Database:
- SQLite

#### 🧠 Dataset:
- [heart.csv on GitHub](https://github.com/GirdharGopal21/Heart-Disease-Prediction-Using-Mchine-Learning/tree/e34936df7611e7c68224db38279d2f64f89117a1/Machine_Learning)

#### 🛠️ IDEs:
- VS Code, PyCharm

#### 🖥️ Operating Systems:
- macOS, Ubuntu, Windows

---

### ▶️ **Run Locally**

```bash
git clone https://github.com/GirdharGopal21/Heart-Disease-Prediction-Using-Mchine-Learning.git
cd Heart-Disease-Prediction-System
python manage.py runserver
```

---

### 🧠 **ML Model Training Snippet**

```python
def prdict_heart_disease(list_data):
    ...
    nn_model = GradientBoostingClassifier(...)
    nn_model.fit(X_train, y_train)
    pred = nn_model.predict([list_data])
    ...
```

---

### 📸 **Output Screenshots**
- Welcome Page
- Admin Dashboard
- Heart Detail Form
- Search Logs
- View Details
- Help Video
- Doctor Records

---

### ⚠️ **Note**
- GitHub Pages is not working.

